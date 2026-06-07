pipeline {
    agent any

    stages {

        stage('Build'){
            steps{
                echo 'Building Application'
                bat 'npm install'
            }
        }

        stage('Test'){
            steps{
                echo 'Testing Application'
                bat 'npm test'
            }
        }

        stage('Deploy'){
            steps{
                echo 'Deploying Application'
            }
        }
    }
}