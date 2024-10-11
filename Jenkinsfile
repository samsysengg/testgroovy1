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
            input message: 'Deploy to production?', ok: 'Proceed', submitter: 'admin'
            echo 'Deploying...'
            // Add your deploy steps here
        }
    }
}
        }
    }

