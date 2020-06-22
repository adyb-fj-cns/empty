pipeline {
  agent any
  stages {
    stage('Step 1') {
      parallel {
        stage('Step 1a') {
          steps {
            sh 'echo "Hello World"'
          }
        }

        stage('Step 1b') {
          steps {
            echo 'Hello World'
          }
        }

      }
    }

    stage('Step 2') {
      steps {
        sh 'echo "Hello World again!"'
      }
    }

  }
}