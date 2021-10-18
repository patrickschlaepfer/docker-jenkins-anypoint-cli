pipeline {
  
  agent any
  
  environment {
    CI = 'true'
  }
  tools { nodejs "NodeJS Latest" }
  
  stages {
    
    stage('Install dependencies') {
      steps {
        sh 'npm install'
        sh 'npm install -g anypoint-cli@latest'
      }
    }

    stage('Running anypoint-cli') {
      steps {
        sh 'anypoint-cli'
      }
    }

  }
}
