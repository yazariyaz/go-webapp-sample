pipeline {
  agent any
  stages {
    stage('run app') {
      steps {
        echo 'Hello'
      }
    }

    stage('build') {
      steps {
        sh 'go run main.go &'
      }
    }

  }
}