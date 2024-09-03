pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                // Clone the Git repository
                git branch: 'main', url: 'https://github.com/shivamchaurasia07/jenkins-pipeline-demo.git'
            }
        }
        stage('Build') {
            steps {
                // Simulate a build step
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                // Simulate a test step
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                // Simulate a deployment step
                echo 'Deploying the application...'
            }
        }
    }
}
