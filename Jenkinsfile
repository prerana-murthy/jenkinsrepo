pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        echo 'deployment successful'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            bat 'mvn -v'
          }
        }

        stage('paralleltest') {
          steps {
            bat 'mvn -v'
          }
        }

      }
    }

  }
}