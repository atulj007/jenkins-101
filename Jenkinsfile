pipeline {
    agent any
    triggers {
        pollSCM 'H/2 * * * *'
            }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                echo "doing Build stuff.."
                '''
              }
        }
         stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "doing test stuff.."
                '''
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

