pipeline {
    agent any
    tools {nodejs "Node-LTS"}
    stages{
        stage('Build'){
            steps{
                sh 'npm install'
            }
        }
        stage('Test'){
            steps{
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}