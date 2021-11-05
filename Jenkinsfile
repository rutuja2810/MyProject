pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello'
          }
        }

        stage('Test') {
          steps {
            sh 'echo "Test a job"'
          }
        }

      }
    }

  }
}