pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo \'Build\''
      }
    }
    stage('Test') {
      steps {
        sh './jenkins/scripts/test.sh'
      }
    }
    stage('Deliver') {
      steps {
        sh './jenkins/scripts/deliver.sh'
      }
    }
  }
  environment {
    CI = 'True'
  }
}