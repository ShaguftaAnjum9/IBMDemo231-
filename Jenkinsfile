pipeline {
  agent none
  stages {
    stage('stage') {
      steps {
        echo 'hi'
      }
    }

    stage('stage1') {
      steps {
        echo 'stage1'
      }
    }

  }
  environment {
    prd = 'server'
  }
}