pipeline {
    agent { 
        node {
            label 'Docker_cloud_agent'
            }
      }
    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
               
               
                
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
              
              
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
