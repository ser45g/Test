pipeline{
  agent{
    node{
      label Docker_Cloud_Agent
    }
  }
  triggers{
    pollSCM '* /2 * * * *'
  }
  stages{
    stage("Build"){
      steps{
        echo "Hello World"
        echo "Building"
      }
    }
    stage("Test"){
      steps{
        echo "Testing"
      }
    }
    stage("Deliver"){
      steps{
        echo "Delivering"
      }
    }
  }
}
