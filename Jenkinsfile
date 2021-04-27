pipeline {
   agent { 
       docker { image 'pytest' }
   }
   stages {
       stage('before') {
           steps {
               println("bbefore")
           }
       }
       stage('para') {
           parallel {
               stage('apple') {
                   steps {
                       println("apple 1")
                       sleep(20 * Math.random())
                       println("apple 2")
                       sh 'python3 -m pytest'
                   }
               }
               stage('banana') {
                   steps {
                       println("banana 1")
                       sleep(20 * Math.random())
                       println("banana 2")
                   }
               }
               stage('peach') {
                   steps {
                       println("peach 1")
                       sleep(20 * Math.random())
                       println("peach 2")
                   }
               }
           }
       }
       stage('after') {
           steps {
               println("aafter")
           }
       }
   }
}
