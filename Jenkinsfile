pipeline {
    agent {
        docker { image 'python:alpine3.19' }
    }
    stages {
        stage('build') {
            steps {
                echo "Building.."
                sh '''
                python --version
                '''
            }
        }
        stage('test') {
            steps {
                echo "Testing.."
                sh '''
                echo "doing test stuff.."
                '''
            }
        }
        stage('deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}