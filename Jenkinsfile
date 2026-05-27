
pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                echo "📦 Building MAIN branch - Production"
            }
        }
        stage('Build') {
            steps {
                echo "🔨 Running production build"
                // yahan real build command aayegi
            }
        }
        stage('Deploy') {
            steps {
                echo "🚀 Deploying to PRODUCTION server"
            }
        }
    }
    
    post {
        success {
            echo "✅ Production deployment successful"
        }
    }
}