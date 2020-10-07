pipeline{
  agent any
  stages{
    
    stage('SCM'){
      steps{
        echo "Git Checkout"
      }
    }
    
    stage('Uplod to Nexus'){
      steps{
        echo "deploy to nexus"
      }
    }
    
   stage('Deploy to Dev'){
      steps{
        echo "deploy to dev"
      }
    }
    
   stage('Deploy to QA'){
      steps{
        echo "deploy to dev"
      }
    }
    
  }
}
