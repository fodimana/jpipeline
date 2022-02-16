pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "This is build number $BUILD_NUMBER from $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}