pipeline {
    agent {
        node{
            label 'ROBOSHOP'
        }
    }

 environment { 
        COURSE= "Jenkins"
    }

options {
    disableConcurrentBuilds()
        timeout(time: 15, unit: 'MINUTES') 
    }

    // Build
    stages {
        stage('Build') {
            steps {
                script {
                    sh """
                        echo "Building.."
                        echo "course is: ${COURSE}"
                        sleep 5
                    """
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    sh """
                        echo "Building.."
                    """
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    sh """
                        echo "Building.."
                    """
                }
            }
        }
    }

     post { 
        always { 
            echo 'I will always say Hello again!'
        }
        success { 
            echo 'I will run when success'
        }
        failure { 
            echo 'I will run when failure'
        }
    }
}