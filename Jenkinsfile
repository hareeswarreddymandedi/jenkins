pipeline {
    agent {
        node{
            label 'ROBOSHOP'
        }
    }
    // Build
    stages {
        stage('Build') {
            steps {
                script {
                    sh """
                        echo "Building.."
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