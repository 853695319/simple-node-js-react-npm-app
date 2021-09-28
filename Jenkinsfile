pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
  environment {
    image = 'node:12-alpine'
    args = '-p 3000:3000'
  }
}