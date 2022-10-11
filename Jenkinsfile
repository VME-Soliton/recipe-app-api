/* Requires the Docker Pipeline plugin */
pipeline {
    agent none
    stages {
        stage('build') {
            agent {
                docker { image 'python:3.9-alpine3.13' }
            }
            steps {
                sh 'python --version'
            }
        }
    }
}
