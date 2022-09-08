pipeline {
    agent any
    stages {
      stage ("jenkins pac") {
        steps {
          script {
            sh """
            echo "hey welcome to pac"
            """
                }
            }
        }
    stage("Code build"){
      steps {
        script {
          sh """
          echo "Hi we are building the code"
          """
        }
      }
    }
    stage("variable delcare"){
      steps {
        script {
          sh """
          var1 = 50
          println "${var1}"
       }   """    
       }
      }
      }
}
     
