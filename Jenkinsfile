pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        sh 'npm install'
        sh 'npm run build'
      }
    }
  }
}