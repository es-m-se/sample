#!groovy
pipeline {
    agent {label 'slave'}
    // agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}


