pipeline {
  agent none
  stages {
    stage('Prebuild') {
      steps {
        sh 'npm audit'
      }
    }
  }
}