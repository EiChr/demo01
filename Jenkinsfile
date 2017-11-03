pipeline {
  agent any
  stages {
    stage('parallel 1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo hallo1'
            sh 'echo hallo1b'
          }
        }
        stage('stage 2') {
          steps {
            sh 'echo hallo2'
          }
        }
      }
    }
  }
}