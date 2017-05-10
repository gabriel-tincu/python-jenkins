pipeline {
    agent any
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
