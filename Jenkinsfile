pipeline {
  agent any
  stages {
    stage('shell') {
      steps {
        sh 'ls'
      }
    }
    stage('sleep') {
      steps {
        sleep 1
      }
    }
  }
  environment {
    ddd = '123'
  }
}