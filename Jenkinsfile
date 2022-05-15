pipeline {
  agent any
  stages {
    stage('welcome') {
      steps {
        echo "welcome jenkins........"
      }
    }
    
     stage('when test') {
       when {
          branch 'develop'     
       }
        steps {
        echo "welcome jenkins when test........"
      }
    }
  }
}
