pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'I am in Dev from dev branch'
                sh 'git --version'
            }
        }
 stage('Testing') {
            steps {
                echo 'I am in Testing from dev branch'
                sh 'python3 --version'
            }
        }
 stage('Production') {
            steps {
                echo 'I am in Production from dev branch'
                sh 'docker --version'
            }
        }
    }
}
