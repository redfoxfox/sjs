pipeline {
  agent {
    node {
      label 'slave_worker'
    }

  }
  stages {
    stage('Source') {
      steps {
        git 'git@github.com:redfoxfox/sjs.git'
      }
    }

  }
  environment {
    COMPLETED_MSG = 'Build done!'
  }
}