pipeline {
    stage('Pull Code'){
        sh 'git clone https://github.com/iPaoKung/gofizzbuzz.git'
    }
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
