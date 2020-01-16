pipeline {
    agent any

    stages {
        stage('version') {
            steps{
                sh "java -version"
                sh "docker version"
                sh "go version"
            }
        }
        stage('Compile') {
            steps {
                sh 'go build'
            }
        }
    }
}