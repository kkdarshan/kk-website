pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'ls -la' // Example build command
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "No tests yet"' // Replace with your test commands
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                sh 'echo "Deploy step"' // Replace with deployment commands
            }
        }
    }
}
