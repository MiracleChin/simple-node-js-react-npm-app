pipeline {
    agent {
        docker {
            image 'node:lts-bullseye-slim' 
            args '-p 3000:3000 -u root' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                echo 'building...'
                sh 'node -v' 
                sh 'npm i'
                sh 'node -v'
            }
        }
    }
}