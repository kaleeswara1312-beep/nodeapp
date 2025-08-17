pipeline {
    agent any
    environment {
        JENKINS_ENV = 'jenkins'
    }

    stages {
        stage('Environment') {
            steps {
                echo 'Dev Environment'
            }
        }

        stage('Installing the package') {
            steps {
                bat 'npm install'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployed the Dev application...'
            }
        }

        stage('Finally') {
            steps {
                echo 'Final stage of the Pipeline'
            }
        }
    }
}
