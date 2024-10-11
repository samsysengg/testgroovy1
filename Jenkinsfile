pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                echo 'Building da...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
        steps {
        script {
            input message: 'Manual approval required: Deploy to environment?', ok: 'Deploy'
            echo 'Deploying...'
            // Add your deploy steps here
        }
    }
}
        }
    }
}
