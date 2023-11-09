pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Start to buil'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing Start'
      }
    }

    stage('Deploy') {
      steps {
        pwsh 'java --version'
      }
    }

  }
}