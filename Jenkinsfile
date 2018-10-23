pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn install'
        echo 'SUCCESS'
      }
    }
    stage('TEST') {
      steps {
        sh 'mvn test'
      }
    }
  }
}