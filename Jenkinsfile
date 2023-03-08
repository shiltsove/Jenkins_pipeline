pipeline {
  agent any
 
  stages {
    stage('Example') {
      steps {
        echo 'Example jenkins pipeline'
      }
    }
  }
//   will be executed after all stages are done
  
  post {
    always {
//       will be executed regardles stages are succefull or failed
      echo 'Post message'
    }
    
  }
}
