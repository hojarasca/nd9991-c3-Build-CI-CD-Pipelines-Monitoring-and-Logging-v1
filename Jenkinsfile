pipeline {
    agent {
        docker { image 'ubuntu:20.04' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'sudo apt-get install tidy -y'
                sh 'uname -a'
            }
        }
    }
}