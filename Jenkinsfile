pipeline {
  agent any
  properties([pipelineTriggers([[$class: 'GitHubPushTrigger']])]) 
  stages {
    stage('start') {
      steps {
        sh 'echo yes'
      }
    }
  }
}
