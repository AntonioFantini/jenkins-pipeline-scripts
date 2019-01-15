@Library('contra-prod')
pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        script {
          executeInProdExecutor('ls -latr', null, false)
        }

      }
    }
  }
}
