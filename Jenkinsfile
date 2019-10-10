pipeline {
  agent {
    dockerfile {
      filename 'DockerFile'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat '  echo \'Testing..\''
      }
    }
  }
  environment {
    DOCKER_TOOLBOX_INSTALL_PATH = 'd:\\Program Files\\Docker Toolbox'
  }
}