pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'tested good'
          }
        }

        stage('Test') {
          steps {
            bat 'echo \'Hello World\''
          }
        }

      }
    }

  }
}