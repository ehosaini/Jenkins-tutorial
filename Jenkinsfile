Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'golang:1.22.0-alpine3.19' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
