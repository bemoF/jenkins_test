pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            sh 'ls'
          }
        }

        stage('test11') {
          steps {
            sh 'ls'
          }
        }

      }
    }

  }
}