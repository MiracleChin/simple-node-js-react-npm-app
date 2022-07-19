pipeline {
    agent {
        docker { image 'current-alpine3.15' }
    }

    stages {
        stage('Build') {
            steps {
                sh 'node --version'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                sh 'node --version'
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'node --version'

                echo 'Deploying....'
            }
        }
    }
}