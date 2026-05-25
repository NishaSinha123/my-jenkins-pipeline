pipeline{
    agent any
    stages{
        stage('Checkout'){
            steps{
                echo 'code github se checkout hogs...'
            }
        }

        stage('Build'){
            steps{
                echo 'Maven se build ho rha hai ...'
            }
        }
        stage('Test'){
            steps{
                echo 'Tests chal rha hai..'
            }
        }
    }

    post{
        always{
            echo 'pipelines complete hone wali hai..'
        }
        success{
            echo 'Build successful hai ...'
        }
        failure{
            echo 'Build failed..'
        }
    }
}