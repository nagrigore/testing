pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     sh 'sudo pip3 install pytest'
                 }
                 }
                 stage('Two') {
                 steps {
                    sh 'sudo python3 -m pytest'
                 }
                 }
         }
}
