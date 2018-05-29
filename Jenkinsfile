pipeline {
  agent {
    label 'jdk8'
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