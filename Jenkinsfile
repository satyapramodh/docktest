pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'env.docker image ls'
      }
    }
    stage('test') {
      steps {
        sh 'pytest'
      }
    }
  }
}