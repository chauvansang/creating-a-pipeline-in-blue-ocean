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
        sh '''#./jenkins/scripts/test.sh
echo \'Test\''''
      }
    }
    stage('Deliver') {
      steps {
        sh '''#./jenkins/scripts/deliver.sh
echo \'Deliver\''''
      }
    }
  }
  environment {
    CI = 'True'
  }
}