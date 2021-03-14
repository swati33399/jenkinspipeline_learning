pipeline {
    agent any

    stages {
        stage('Fetching Code from GitHub') {
            steps {
                echo 'git pull'
            }
        }
        stage('Build') {
            steps {
                echo 'maven build'
            }
        }
        stage('Test') {
            steps {
                echo 'maven test'
            }
        }
        stage('Deploy to webserver') {
            steps {
                echo 'deploy to tomcat'
            }
        }
    }
}
