pipeline{
  
  agent any
  
  stages{
  
    stage('First Stage'){
      when {
          changeRequest()
        }
      steps{
        
        
        sh 'This branch has PR ---------'
      }      
    }
    
  }
  
}
