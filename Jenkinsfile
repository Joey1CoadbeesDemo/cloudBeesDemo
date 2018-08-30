pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      environment {
        MY_NAME = 'Mary'
      }
      steps {
        echo MY_NAME
        sh 'java -version'
      }
    }
  }
}