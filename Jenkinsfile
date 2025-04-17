pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/Aiman-ui/jenkins-repo.git'
            }
        }
        stage('Build') {
            steps {
                echo ' we are building something here...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests now...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying app...'
            }
        }
    }
}
