pipeline {
    agent any
    environment {
        ENV_NAME = 'UAT'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building for ${ENV_NAME} environment"
                // Add build steps here
            }
        }
        stage('Test') {
            steps {
                echo "Running tests for ${ENV_NAME} environment"
                // Add test steps here
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying to ${ENV_NAME} environment"
                // Add deployment steps here
            }
        }
    }
}
