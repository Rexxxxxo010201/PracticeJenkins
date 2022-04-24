pipeline{
  agent any
  stages{
    stage('Testing'){
      steps{
        echo 'running Tests'
    }
   }
   stage('Build'){
   steps{
   echo 'Building jar files...'
   bat 'python3 practice.py'
   }
  }
 }
}
