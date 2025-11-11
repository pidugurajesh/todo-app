pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/pidugurajesh/todo-app.git'
            }
        }

        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests yet, skipping...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy step will be added later with Docker'
            }
        }
    }
}
