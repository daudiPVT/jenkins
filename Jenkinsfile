pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // You can add your build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // You can add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // You can add your deployment commands here
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline executed successfully!'
            // You can add post-success actions here
        }
        failure {
            echo 'Pipeline execution failed!'
            // You can add post-failure actions here
        }
    }
}
