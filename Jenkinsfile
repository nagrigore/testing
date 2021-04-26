pipeline {
    agent any
    stages {
        stage('install pytest') {
            steps {
                sh 'pip3 install pytest'
            }
            
        stage('build') {
            steps {
                sh 'python3 -m pytest'
            }
            
        }
    }
}
