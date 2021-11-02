pipeline {
    agent { label 'My-Pipeline' }
    stages {
        stage('build') {
            steps {
                sh 'pwd'
                sh 'mvn --version'
            }
        }
    }
}
