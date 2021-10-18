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
      }
    }

    
  }
}
