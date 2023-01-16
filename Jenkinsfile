pipeline {
  agent any
  stages {
    stages ('Build') {
      steps {
        echo 'Build step'
        sleep 10
      }
    }
    stage ('Test') {
      steps {
        echo 'Test step'
        
      }
      
    }
    stage ('deploy') {
      steps {
        echo 'deploy step'
        sleep 10
        
      }
      
    }
    stage ('Docker') {
      steps {
        echo 'Image step'
        
      }
    }
  }
} 
