pipeline {
    agent {
        docker { image 'ubuntu:18.04' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}