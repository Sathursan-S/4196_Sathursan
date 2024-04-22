#!groovy
pipeline {
    agent none
    
    stages {
        stage('Docker compose') {
            steps {
                script {
                    sh 'docker-compose up -d'
                }
            }
        }
    }
}