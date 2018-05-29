pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Hello ${MY_NAME}') {
      steps {
        echo '2nd time building'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Venki'
  }
}