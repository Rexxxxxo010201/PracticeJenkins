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
     bat 'gcc -o program program.cpp'
   }
  }
 }
}
