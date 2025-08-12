pipeline {
    agent any

    tools {
        maven 'Maven'    // Jenkins में जो Maven tool का नाम है, वही लिखो
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}

