pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo '✅ Clonage terminé automatiquement'
            }
        }

        stage('Start Docker Compose') {
            steps {
                sh 'docker-compose up -d'
            }
        }

        stage('Check Containers') {
            steps {
                sh 'docker ps'
            }
        }
    }
}
