pipeline {
  agent {
    docker {
      image 'node:7-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'node --version'
        sh 'node --help'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
        echo 'Testing Done'
      }
    }

  }
}