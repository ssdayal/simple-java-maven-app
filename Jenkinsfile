pipeline {
  agent none
  stages {
    stage('maven-build') {
      steps {
        sh '''mvn clean install skip=true
'''
      }
    }

  }
}