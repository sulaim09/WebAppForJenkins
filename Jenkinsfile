pipeline {
    agent any
    tools {
        maven '3.9.4'
    }
    stages {
        stage('Clean and Install') {
            steps {
               bat 'mvn clean install'
            }
        }
        stage('Package') {
            steps {
               bat 'mvn package'
            }
        }
    }
}
