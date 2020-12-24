pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Build mesage'
      }
    }

    stage('Test') {
      steps {
        echo 'Test message'
        sh '''pwd
whomai'''
      }
    }

  }
}