pipeline{
    agent any
    stages{
        stage('Make directory'){
            steps{
                sh "mkdir ~/jenkins-tutorial-test || true"
            }
        }
        stage('make files'){
            steps{
                sh "touch ~/jenkins-tutorial-test/file1"
            }
        }
        stage('run run.sh'){
            steps{
                sh "run.sh"
            }
        }
    }
}