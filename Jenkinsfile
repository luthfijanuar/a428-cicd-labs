pipeline {
    agent {
        docker {
            image 'node:16.20.2-alpine3.18' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install --verbose'
            }
        }
    }
}