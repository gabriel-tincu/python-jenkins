pipeline {
    agent { docker 'python:3.5.1' }
    stages {
        stage('build') {
            steps {
                sh 'ls -al' 
                sh 'pwd' 
                sh 'pip install -r requirements.txt'
            }
        }
    }
}
