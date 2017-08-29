pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './jenkins/build.sh'
        archiveArtifacts '**/surefire-reports/**/*.xml'
      }
    }
    stage('Test') {
      steps {
        echo 'test'
      }
    }
  }
}