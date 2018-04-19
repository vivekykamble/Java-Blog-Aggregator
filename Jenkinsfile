pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''mvn clean
'''
        sh 'cd $home'
      }
    }
    stage('Change Directory') {
      steps {
        sh 'cd $home'
      }
    }
  }
}