pipeline{
  agent any
  stages{
    stage('Build'){
      // steps{
      //   "This is random"
      //   build 'PES1UG21CS235-1'
      //   sh 'g++ hello.cpp -o output'
      }
    }
    
    // stage('Test'){
    //   steps{
    //     sh 
      }
    }
    
    stage('Deploy'){
      steps{
        echo 'deploy'
      }
    }
  }
  post{
    failure{
      error 'Pipeline failed'
    }
  }
}
