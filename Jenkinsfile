pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello world'
      }
    }
    stage('Test One') {
      parallel {
        stage('Test') {
          steps {
            echo 'test two'
          }
        }
        stage('') {
          steps {
            echo 'test one'
          }
        }
      }
    }
  }
}