pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     sh 'python3 --version'
                 }
                 }
                 stage('Two') {
                 steps {
                    sh 'python3 -m pytest'
                 }
                 }
         }
}
