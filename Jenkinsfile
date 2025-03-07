pipeline{
  agent any
  stages{
    stage('create new file') {
      steps { 
        sh 'touch new_file.txt'
      }
    }
    stage('Print msg') {
      steps { 
        echo 'hello from pipe'
      }
    }
  }
}
