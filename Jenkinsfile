pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the app...'
                // For example, you can run: sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // For example, run: sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the app...'
                // You can add deploy commands like Docker build/push here
            }
        }
    }
}
