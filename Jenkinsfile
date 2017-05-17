pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        parallel(
          "Build": {
            echo 'build'
            bat 'npm -v'
            bat 'npm install'
            bat 'grunt -v'
            
          },
          "error": {
            bat 'grunt'
            
          }
        )
      }
    }
  }
}