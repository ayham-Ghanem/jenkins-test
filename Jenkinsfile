pipeline{
  agent any
  stages{
    
    stage('Print msg') {
      steps { 
        echo 'hello from pipe'
      } 
  }
    stage('Python') {
        steps { 
          bat 'python main.py'
        }
      }
}
}
