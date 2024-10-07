pipeline {
    agent {
        docker {
            image 'node:20.18.0-alpine3.20'
            args '-w /workspace/My-Project -v /c/Users/manav/.jenkins/workspace/My-Project:/workspace/My-Project'
        }
    }
    stages {
        stage('Build') {
            steps {
                // Your build steps here
                sh 'node --version'
            }
        }
    }
}
