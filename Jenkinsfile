pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'npm run dev'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'pwd'
                sh 'ls'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'pwd'
                sh 'ls'
            }
        }
    }
}