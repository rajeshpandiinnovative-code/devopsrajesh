pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/rajeshpandiinnovative-code/devopsrajesh.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
