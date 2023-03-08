pipeline {
  agent any
 
  stages {
    stage('Example') {
      steps {
        echo 'Example jenkins pipeline'
      }
    }
  }
//   will be executed after all stages are  passed
  
  post {
    echo 'Post message'
  }
}
