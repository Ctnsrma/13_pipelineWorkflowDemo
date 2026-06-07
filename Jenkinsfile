pipeline {
    agent any
    stages {
        stage('Checkout'){
            steps{
                git 'https://github.com/Ctnsrma/13_pipelineWorkflowDemo'
            }
        }
        stage('Build'){
            steps{
                bat 'npm install'
            }
        }
        stage('Test'){
            steps{
                bat 'npm test'
            }
        }
        stage('Deploy'){
            steps{
                bat 'node app.js'
            }
        }
    }
}