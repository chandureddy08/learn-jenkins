pipeline {
    agent any
    options{
        timeout(time: 1, unit: 'SECONDS')
        disableConcurrentBuilds()
    }
    stages{
        stage('Build') {
            steps{
            sh 'echo this is build stage'
            }
        }
        stage('Test') {
            steps{
            sh 'echo this is test stage'
            sh 'sleep 10'
            }
        }
         stage('Deploy') {
            steps{
            sh 'echo this is Deploy stage'
            }
        }
    }
}