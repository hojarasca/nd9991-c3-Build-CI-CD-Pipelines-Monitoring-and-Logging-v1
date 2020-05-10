pipeline {
    agent {
        docker { image 'imega/tidy' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'tidy --version'
            }
        }
    }
}