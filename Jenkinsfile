pipeline {
    agent any

    stages {
        stage('Checkout project') {
            steps {
                script {
                    // Checkout the project from GitHub
                    git branch: 'main',
                        credentialsId: 'none',
                        url: 'https://github.com/Isha-Ipsita/employeeProjPortal.git'
                }
            }
        }
    }
}
