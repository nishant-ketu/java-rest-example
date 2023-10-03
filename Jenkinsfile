pipeline {
    agent any
    stages {
        stage('Git Tag') {
            steps {
                // Check out code from a Git repository
                git rev-parse --short HEAD
            }
        }
        stage('Build') {
            steps {
                // Build your project (replace 'your-build-command' with the actual build command)
                echo 'your-build-command'
            }
        }
        stage('Deploy') {
            steps {
                // Deploy your project (replace 'your-deploy-command' with the actual deploy command)
                echo 'your-deploy-command'
            }
        }
    }
    post {
        success {
            echo 'Pipeline succeeded! This is where you can notify or do post-build actions.'
        }
        failure {
            echo 'Pipeline failed! This is where you can handle failure scenarios.'
        }
    }
}
