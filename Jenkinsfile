pipeline {
  agent any
  stages {
    
    stage("Checkout Code")
    {
      steps
      {
        git branch: 'main',      
        url: 'https://github.com/vivekpaliwal-87/testrepo.git'
      }
    }
    
    stage('Build Code') {
            steps {
                bat "mvn clean package"
            }
        }
    

  }
}
