/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:16.17.1-alpine' } }
    stages {
        stage('master') {
            steps {
                sh 'node --version'
            }
        }
    }
}