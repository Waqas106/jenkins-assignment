pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/<your-username>/jenkins-assignment.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build Stage Running..."
                bat 'dir'
            }
        }

        stage('Test') {
            steps {
                echo "Testing (example only)"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deployment simulated..."
            }
        }
    }

    post {
        success {
            echo "Pipeline completed successfully!"
        }
        failure {
            echo "Pipeline failed!"
        }
    }
}
