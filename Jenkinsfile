/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'esumana/golang:1.19.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}