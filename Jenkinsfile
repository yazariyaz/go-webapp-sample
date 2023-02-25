pipeline {
  agent none
  stages {
    stage('run app') {
      steps {
        echo 'Hello'
      }
    }

    stage('build') {
      steps {
        sh 'sh ./...'
      }
    }

  }
}