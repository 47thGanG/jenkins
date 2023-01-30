pipeline {
    agent any

    stages {
        stage('docker-compose install') {
            steps {
                sh 'sudo apt install docker-compose'
            }
        }
        stage('docker-compose build and up') {
            steps {
                sh 'docker-compose build'
                sh 'docker-compose up -d'
            }
        }
    }
}
