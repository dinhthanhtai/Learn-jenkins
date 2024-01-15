pipeline {
    agent {
        docker { image 'node:20-alpine3.18' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'docker --version'
            }
        }
    }
}
