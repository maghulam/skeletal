pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        echo 'Bee Buzz !'
        echo '$BUZZ_NAME'
      }
    }

    stage('Buzz Test') {
      steps {
        echo 'Buzz Test Stage'
      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
  }
}