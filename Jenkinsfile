pipeline{
  
  agent any
  
  stages{
  
    stage('First Stage'){
      
      steps{
        when {
          changerequest()
        }
        
        sh 'This branch has PR ---------'
      }      
    }
    
  }
  
}
