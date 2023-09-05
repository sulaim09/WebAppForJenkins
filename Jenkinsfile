pipeline {
    agent any
    tools {
        maven '3.6.3'
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
        stage('tomcate') {
            steps {
               sh 'touch kkr'
            }
        } 
    }
}
