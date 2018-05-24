#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat 'set'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                bat 'ipconfig'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                bat 'mvn --version'
            }
        }
    }
}
