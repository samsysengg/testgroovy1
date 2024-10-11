pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Manual Approval') {
            steps {
                script {
                    input message: 'Proceed with Deploy?', ok: 'Yes'
                }
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying after approval...'
            }
        }
    }
}
