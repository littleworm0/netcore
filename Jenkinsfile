pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat '  "docker build -t mcore ."'
      }
    }
  }
  environment {
    DOCKER_TOOLBOX_INSTALL_PATH = 'd:\\Program Files\\Docker Toolbox'
  }
}