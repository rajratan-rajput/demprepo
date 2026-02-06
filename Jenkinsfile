pipeline {    
      agent any    
        
       stages {        
         stage('Checkout') 
         {            
                 steps {
                        echo "Cloning the repository..."                
                         git branch: 'master', url: 'https://github.com/kylhgr/Hello-World-Python.git'                             	}        
         }        
         stage('Build') {            
                 steps {  echo "Build step (simulated)...“   }        
         }        
        stage('Test') {            
                 steps {  echo "Test step (simulated)..."     }        
        }         
       stage('Deploy') {           
                   steps { echo "Deploy step (simulated)..."   }        
        }    
     }   //close stages 
     post {      success {            echo "Pipeline succeeded!"        }        
                    failure {            echo "Pipeline failed!"        }    
             }
 } //close pipeline
