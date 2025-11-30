pipeline {
    agent any
    
    // Lab 11: Environment Variables
    environment {
        NEW_VERSION = '1.3.0'
    }
    
    stages {
        stage('Build') {
            steps {
                echo 'Building Project...'
                echo "Building version ${NEW_VERSION}"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Project...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Project...'
            }
        }
    }
    
    // Lab 11: Post Build Actions
    post {
        always {
            echo 'Lab 11: Post build condition running successfully!'
        }
    }
}
