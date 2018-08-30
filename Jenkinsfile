pipeline {
  agent {
    label 'jdk7'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World'
        sh 'java -version'
      }
    }
  }
}