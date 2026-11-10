
pipeline {
    agent any

    stages {
        stage('Check Java') {
            steps {
                bat 'java -version'
            }
        }

        stage('Check Git') {
            steps {
                bat 'git --version'
            }
        }

        stage('Check Workspace') {
            steps {
                bat 'dir'
            }
        }
    }
}
