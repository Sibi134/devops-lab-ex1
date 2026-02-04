pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Checking out code from GitHub..."
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Running build step..."
                // Example build command (change based on your project)
                sh 'echo Build successful'
            }
        }

        stage('Test') {
            steps {
                echo "Running test cases..."
                // Example test command (change based on your project)
                sh 'echo Tests passed'
            }
        }
    }
}
