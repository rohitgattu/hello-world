pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "Hello World"'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "This is test phase"'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "This is deploy phase"'
      }
    }

  }
}