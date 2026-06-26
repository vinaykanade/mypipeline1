pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'I am in Dev from prod branch'
                sh 'git --version'
            }
        }
 stage('Testing') {
            steps {
                echo 'I am in Testing from prod branch'
                sh 'python3 --version'
            }
        }
 stage('Production') {
            steps {
                echo 'I am in Production from prod branch'
                sh 'docker --version'
            }
        }
    }
}
