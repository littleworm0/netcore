pipeline {
  agent {
    docker {
      args '-p 9011:9011'
      image 'mycore3'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat 'bat "docker build"'
      }
    }
  }
}