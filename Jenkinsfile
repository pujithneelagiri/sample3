pipeline {
    agent any

    stages {
        stage('Build') {
            stage(' checkout') {
                git checkout scm
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying to production'
            }
        }
    }
}
