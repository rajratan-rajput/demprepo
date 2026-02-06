pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Cloning the repository..."
                git branch: 'main', url: 'https://github.com/rajratan-rajput/demprepo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build step (simulated)..."
            }
        }

        stage('Test') {
            steps {
                echo "Test step (simulated)..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy step (simulated)..."
            }
        }
    }

    post {
        success {
            echo "Pipeline succeeded!"
        }
        failure {
            echo "Pipeline failed!"
        }
    }
}
