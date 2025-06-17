pipeline {
    agent any
    tools {
        maven 'Maven_Latest'
    }
    stages {
        stage('Build') {
            steps {
                echo "testing pipeline"
                sh 'pwd'
                sh 'ls -ltr'
                sh 'mvn --version'
            }
        }
    }
}
