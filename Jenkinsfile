pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'mvn clean install'
      }
    }
    stage('error') {
      steps {
        echo 'OK'
      }
    }
  }
}