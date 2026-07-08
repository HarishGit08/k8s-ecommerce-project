pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Repository checked out successfully!'
                sh 'pwd'
                sh 'ls -R'
            }
        }

        stage('Verify Files') {
            steps {
                sh 'ls backend'
                sh 'ls frontend'
                sh 'ls mysql'
                sh 'ls jenkins'
            }
        }

        stage('Success') {
            steps {
                echo 'CI Pipeline Executed Successfully!'
            }
        }
    }
}
