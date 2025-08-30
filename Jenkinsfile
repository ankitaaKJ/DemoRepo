pipeline{
  
  agent any
  
  stages{
  
    stage('First Stage'){
      when {
        changeRequest()
      }
      steps{
        sh 'echo "ChangeRequest Block from Dev Branch Jenkinsfile"'
      }      
    }
    
  }
  
}
