pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Hello World') {
      steps {
        echo '2nd time building'
        sh 'java -version'
        echo 'Hello ${MY_NAME}'
      }
    }
  }
  environment {
    MY_NAME = 'Venki'
  }
}