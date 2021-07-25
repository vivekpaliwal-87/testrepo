pipeline {
  agent any
  stages {
    
    stage("git")
    {
      steps
      {
        git branch: 'main',      
        url: 'ssh://git@github.com/vivekpaliwal-87/testrepo.git'
      }
    }
    

  }
}
