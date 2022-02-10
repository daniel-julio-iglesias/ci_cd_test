pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('Build01') {
            steps {
                sh 'python --version'
                sh 'pwd'
            }
        }
        stage('Build02') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
