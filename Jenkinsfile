pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "in build"'
        sh 'npm install'
      }
    }
    stage('Test') {
      steps {
        sh 'echo "In testing"'
      }
    }
  }
}