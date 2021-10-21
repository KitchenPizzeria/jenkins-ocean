pipeline {
  agent any
  stages {
    stage('Display wagwan') {
      steps {
        echo 'wagwan'
        sleep 1
      }
    }

    stage('Display Python Version') {
      parallel {
        stage('Display Python Version') {
          steps {
            sh 'python --version'
          }
        }

        stage('Display node version') {
          steps {
            sh 'echo this is a stage'
          }
        }

      }
    }

  }
}