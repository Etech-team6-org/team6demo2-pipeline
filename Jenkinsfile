pipeline {
    agent any
    stages {
        stage('Henrietta') {
            steps {
                sh 'ps -ef'
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('Idris') {
            steps {
                sh 'ps -ef'
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('jojo') {
            steps {
                sh 'lscpu'
                sh 'sudo systemctl status jenkins'
            }
        }
    }
}