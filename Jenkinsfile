pipeline{
  
  agent any
  
  stages{
  
    stage('First Stage'){
      when {
        changeRequest()
      }
      
      steps{        
        
        sh 'echo "This branch has PR ---------"'
      }      
    }
    
  }
  
}
