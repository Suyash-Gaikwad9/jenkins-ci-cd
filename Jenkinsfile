pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git url: 'git@github.com:Suyash-Gaikwad9/jenkins-ci-cd.git', credentialsId: ''
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}

