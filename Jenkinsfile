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
       stage('Test') {
            steps {
                echo 'Pipeline in testing stage'
                sh 'cat Jenkinsfile'
            }
        }
    }
}
