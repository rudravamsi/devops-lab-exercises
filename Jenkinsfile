pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo Hello from Jenkins Pipeline Lab 5 > pipeline-output.txt'
            }
        }
        stage('Test') {
            steps {
                bat 'echo Running tests > test-output.txt'
            }
        }
    }
}