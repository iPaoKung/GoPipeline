pipeline {
    agent { dockerfile true }
    stages {
        stage('Pull Code'){
            sh 'git clone https://github.com/iPaoKung/gofizzbuzz.git'
        }
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
