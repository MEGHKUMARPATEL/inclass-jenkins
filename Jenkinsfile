pipeline {
    agent {
        docker {
            image 'node:20.18.0-alpine3.20'
            args '-u root:root -w /c/Users/manav/.jenkins/workspace/My-Project' // Adjusting path
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
