pipeline {
    agent { 
        node {
            label 'Docker_Cloud_Agent'
            }
      }
    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                cd myapp
               
                
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                cd myapp
              
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
