pipeline {
    agent { label 'My-Pipeline' }
    stages {
        stage('checkout') {
            steps {
                sh 'pwd'
                sh 'mvn --version'
            }
        }
    }
}
