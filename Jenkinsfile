pipeline {
 agent {
        docker { image 'node:7-alpine' }
  }
 
 stages {
    stage('Build') {
      steps {
        sh 'echo Build'
      }
    }
  stage('Test') {
      steps {
        sh 'echo Test'
      }
    }
 
 stage('Infra') {
      steps {
        sh 'echo Infra'
      }
    }
  stage('Deploy') {
      steps {
        sh 'echo Deploy'
      }
    }
  stage('Full Test') {
      steps {
        sh 'echo FullTest'
      }
    }
 }
}
