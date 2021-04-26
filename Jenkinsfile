pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     sh 'python3 -m pip3 install pytest'
                 }
                 }
                 stage('Two') {
                 steps {
                    sh 'python3 -m pytest'
                 }
                 }
         }
}
