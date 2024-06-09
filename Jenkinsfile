pipeline {
  agent {
    node('master || built-in')
  }
  stages {
    stage('Log hard drives status') {
      steps {
        script {
          sh 'df -h'
        }
      }
    }
  }
}