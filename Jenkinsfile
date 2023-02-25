pipeline {
  agent {
    node {
      label 'centos-build'
    }

  }
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