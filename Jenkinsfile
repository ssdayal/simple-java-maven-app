pipeline {
  agent any
  stages {
    stage('maven-build') {
      steps {
        sh './jenkins/mvn clean package'
      }
    }

  }
}