pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        build 'PES1UG21CS235-1'
        sh 'g++ hprad.cpp -o output'
      }
    }
    
    stage('Test'){
      steps{
        sh './output'
      }
    }
    
    stage('Deploy'){
      steps{
        echo 'Not'
      }
    }
  }
  post{
    failure{
      error 'Pipeline failed'
    }
  }
}
