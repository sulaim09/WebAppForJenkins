pipeline {
    agent any
    tools {
        maven "3.8.6"
    }
    stages {
        stage('Clean and Install') {
            steps {
                // install
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
