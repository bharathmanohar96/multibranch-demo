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
    stage('deploy to test') {
       when {
          branch 'test'     
       }
        steps {
        echo "test deploy........"
      }
    }
    stage('deploy to Prod') {
       when {
          branch 'main'     
       }
        steps {
        echo "main branch deploy........"
      }
    }
  }
}
