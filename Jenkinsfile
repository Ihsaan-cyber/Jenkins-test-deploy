pipeline {
    agent any

    stages {
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