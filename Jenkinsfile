pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "salut"'
          }
        }

        stage('test') {
          steps {
            echo 'echo "coucou"'
          }
        }

      }
    }

  }
}