pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build'
        bat 'npm -v'
        bat 'npm install'
      }
    }
  }
}