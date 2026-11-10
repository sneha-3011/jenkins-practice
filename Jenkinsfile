
/*pipeline {
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
*/

pipeline {
    agent any

    stages {

        stage('Check Java') {
            steps {
                bat 'java -version'
                bat 'javac -version'
            }
        }

        stage('Compile') {
            steps {
                bat 'javac Main.java'
            }
        }

        stage('Run Application') {
            steps {
                bat 'java Main'
            }
        }
    }
}
