pipeline {

  agent any
  options {
    ansiColor('xterm')
  }

  environment {
    CI = 'true'
  }
  tools { nodejs "NodeJS Latest" }

  stages {

    stage('Running anypoint-cli') {
      steps {
        sh 'anypoint-cli'
      }
    }

  }
}
