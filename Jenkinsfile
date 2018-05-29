pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Hello World') {
      steps {
        echo '2nd time building'
        sh 'java -version'
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
      }
    }
  }
  environment {
    MY_NAME = 'Venki'
    TEST_USER = credentials('test-user')
  }
}