pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "This is $BUILD_NUMBER from $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}