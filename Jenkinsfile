pipeline {
    agent any
    tools {
        maven "3.8.1"
    }
    stages {
        stage('Clean and Install') {
            steps {
                // install
               sh "mvn clean install"
            }
        }
        stage('Package') {
            steps {
               sh "mvn package"
            }
        } 
    }
}
