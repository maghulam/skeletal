pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        echo 'Bee Buzz !'
      }
    }

    stage('Buzz Test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}