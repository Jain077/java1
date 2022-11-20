pipeline {
  agent any
  tools {
    maven "3.6.8"
  }
  stages {
    stage('Clean and Install') {
      steps {
        sh 'mvn clean install'
      }
    }
    stage('Package') {
      steps {
        sh 'mvn package'
      }
    }
  }
}
