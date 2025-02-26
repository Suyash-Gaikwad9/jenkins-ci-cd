pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git url: 'git@github.com:Suyash-Gaikwad9/jenkins-ci-cd.git', credentialsId: 'ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIFi8a8x+4URl4mwwR3NY+VD4ELyHuzTjagdRHBYSnqQs suyash.gaikwad21@vit.edu'
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

