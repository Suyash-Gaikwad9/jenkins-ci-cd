pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/YOUR-USERNAME/jenkins-ci-cd-demo.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t myapp:latest .'
            }
        }

        stage('Run Tests') {
            steps {
                sh 'docker run --rm myapp:latest echo "Running tests..."'
            }
        }
    }
}

