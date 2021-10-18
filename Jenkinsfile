pipeline {
  
  agent any
  
  environment {
    CI = 'true'
  }
  tools { nodejs "NodeJS Latest" }
  
  stages {
    stage('Build') {
      steps {
        sh 'npm config ls'
      }
    }
  }
}
