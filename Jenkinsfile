pipeline{
  agent any
  stages{
    stage('create new file') {
      steps { 
        bat 'touch new_file.txt'
      }
    }
    stage('Print msg') {
      steps { 
        echo 'hello from pipe'
      }
      stage('Python') {
      steps { 
        bat 'python main.py'
      }
    }
  }
}
}
