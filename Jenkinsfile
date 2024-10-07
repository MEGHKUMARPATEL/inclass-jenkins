pipeline {
    agent {
        docker {
            image 'node:20.18.0-alpine3.20'
            args '-u root:root' // This might help with permissions issues
        }
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
