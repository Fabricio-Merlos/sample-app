pipeline {
    agent any
    stages {
        stage('Build & Run') {
            steps {
                sh 'bash ./sample-app.sh'
            }
        }
        stage('Test') {
            steps {
                sh 'docker ps | grep -q "samplerunning"'
            }
        }
    }
}
