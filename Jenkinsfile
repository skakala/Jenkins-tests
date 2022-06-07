pipeline {
    agent { docker { image 'golang:1.17.6-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
