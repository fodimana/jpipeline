pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'This is $BUILD_NUMBER of job $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}