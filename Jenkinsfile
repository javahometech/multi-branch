pipeline{
  agent any
  stages{
    
    stage('SCM'){
      when {
        branch 'develop'
      }
      steps{
        echo "Git Checkout"
      }
    }
    
    stage('Uplod to Nexus'){
       when {
        branch 'develop'
       }
      steps{
        echo "deploy to nexus"
      }
    }
    
   stage('Deploy to Dev'){
       when {
        branch 'develop'
      }
      steps{
        echo "deploy to dev"
      }
    }
    
   stage('Deploy to QA'){
      when {
        branch 'release'
      }
      steps{
        echo "deploy to dev"
      }
    }
    
    stage('Deploy to Production'){
      when {
        branch 'main'
      }
      steps{
        echo "deploy to dev"
      }
    }
    
  }
}
