pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        parallel(
          "test": {
            sh 'echo test'
            
          },
          "asdfasdf": {
            echo 'asdfasdf'
            
          }
        )
      }
    }
  }
}