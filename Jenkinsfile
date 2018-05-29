pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('HelloWorld') {
      steps {
        echo '2nd time building'
        sh 'java -version'
      }
    }
  }
}