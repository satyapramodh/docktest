pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
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