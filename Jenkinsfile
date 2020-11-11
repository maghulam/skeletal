pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        echo 'Bee Buzz !'
        echo '${BUZZ_NAME}'
      }
    }

    stage('Buzz Test') {
      parallel {
        stage('Buzz Test') {
          steps {
            echo 'Buzz Test Stage'
          }
        }

        stage('Buzz Test A') {
          steps {
            echo 'Parallel Stage A'
          }
        }

        stage('Buzz Test B') {
          steps {
            echo 'Parallel Stage B'
          }
        }

      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
  }
}