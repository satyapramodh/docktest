pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'docker image ls'
      }
    }
    stage('test') {
      steps {
        sh 'pytest'
      }
    }
  }
}