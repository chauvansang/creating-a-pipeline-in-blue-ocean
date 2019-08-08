pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo \'Build success\''
      }
    }
    stage('Test') {
      steps {
        sh 'echo \'Test success\''
      }
    }
    stage('Deliver') {
      steps {
        sh 'echo \'Deliver success\''
      }
    }
  }
  environment {
    CI = 'True'
  }
}