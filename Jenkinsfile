pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'mvn compile'
      }
    }

    stage('testing') {
      steps {
        sh 'mvn test -x'
      }
    }

  }
}