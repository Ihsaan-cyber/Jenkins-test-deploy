pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Ihsaan-cyber/Jenkins-test-deploy.git'
            }
        }

        stage('Deploy') {
            steps {
                bat '''
                if not exist C:\\deploy mkdir C:\\deploy
                copy index.html C:\\deploy\\index.html
                '''
            }
        }
    }
}