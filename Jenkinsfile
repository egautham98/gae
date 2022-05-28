pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo env.BUILD_NUMBER + ' and also the ' + env.MPEG
      }
    }

  }
  environment {
    MPEG = '1'
  }
}
