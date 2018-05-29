pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Step'
      }
    }
    stage('Test') {
      steps {
        sh 'java -version'
        echo 'At Test step'
      }
    }
  }
}