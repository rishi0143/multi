pipeline {
    agent any

    tools {
        jdk 'jdk-17'
        maven 'mvn-3.6'
    }

    stages {

        stage('Maven Compile') {
            steps {
                sh 'mvn compile'
            }
        }

        stage('Maven Test') {
            steps {
                sh 'mvn test'
            }
        }

        stage('Maven Package') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
