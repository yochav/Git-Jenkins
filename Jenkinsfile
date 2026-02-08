pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Pipeline triggered by GitHub webhook'
                sh 'ls -l'
            }
        }
    }
}
