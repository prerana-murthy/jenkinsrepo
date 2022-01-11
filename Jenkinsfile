pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        echo 'deployment successful'
      }
    }

    stage('test') {
      steps {
        bat 'mavn -v'
      }
    }

  }
}