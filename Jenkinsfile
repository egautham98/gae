pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo env.BUILD_NUMBER+' and also the '+env.MPEG
      }
    }

    stage('publish') {
      agent any
      steps {
        sh 'echo "$BUILD_NUMBER"'
      }
    }

  }
  environment {
    MPEG = '1'
  }
}