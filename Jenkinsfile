pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'echo "Hello"
                sh 'echo $PATH'
                sh 'pwd'
                sh 'ls -al'
            }
        }
    }
}
