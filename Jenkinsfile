pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "in build"'
        sh 'grunt'
      }
    }
    stage('Test') {
      steps {
        sh 'echo "In testing"'
      }
    }
  }
}