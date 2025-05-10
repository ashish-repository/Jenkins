pipeline {
    agent any
    stages{
        stage('clone github repo') {
            steps{
                echo'cloning repo from github'
            }
        }
        stage('Test code') {
            steps{
                echo 'Testing source code'
            }
        }
        stage('Build') {
            steps{
                echo 'Creating artifacts'
            }
        }
        stage('deploy-dev') {
            steps{
                echo 'Deploying code in dev'
            }
        }
        stage('deploy-UAT') {
        }
    }
}