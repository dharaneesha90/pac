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
  }
}
