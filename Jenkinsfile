pipeline {
    agent { label 'My-Pipeline' }
    stages {
        stage('checkout') {
            steps {
                sh 'pwd'
                sh 'echo hello'
                sh 'mvn --version'
            }
        }
    }
}
