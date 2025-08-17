pipeline {
    agent any
    environment {
        JENKINS_ENV = 'jenkins'
    }

    stages {
        stage('Environment') {
            steps {
                echo 'Main Environment'
            }
        }

        stage('Installing the package') {
            steps {
                sh 'npm install'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployed the Main application...'
            }
        }
    }
}
