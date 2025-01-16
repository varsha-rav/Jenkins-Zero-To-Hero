pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Testing') {
      steps {
        sh 'node --version'
      }
    }
  }
}
