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
            pwd(tmp: true)
          }
        }

      }
    }

  }
}