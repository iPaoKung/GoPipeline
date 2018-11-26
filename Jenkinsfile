pipeline {
    agent { dockerfile true }
    stages {
        stage('Pull Code'){
            git clone https://github.com/iPaoKung/gofizzbuzz.git
        }
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
