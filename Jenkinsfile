
pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                echo "🔧 Building FEATURE branch - Login feature"
            }
        }
        stage('Build') {
            steps {
                echo "🔨 Running feature branch build"
            }
        }
        stage('Test') {
            steps {
                echo "🧪 Running unit tests for login feature"
            }
        }
        // No deploy stage for feature branches
    }
    
    post {
        success {
            echo "✅ Feature branch build passed"
        }
    }
}