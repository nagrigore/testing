pipeline {
         agent any
         stages {
            stage('CheckoutModule1') {
                steps {
                    sh 'mkdir -p Module1'
                    dir("Module1")
                    {
                        git branch: "main",
                        url: 'https://github.com/nagrigore/testing.git'
                    }
                }
            }

            stage('CheckoutModule2') {
                steps {
                    sh 'mkdir -p Module2'
                    dir("Module2")
                    {
                        git branch: "main",
                        url: 'https://github.com/nagrigore/testing2.git'
                    }
                }
            }
         }
}
