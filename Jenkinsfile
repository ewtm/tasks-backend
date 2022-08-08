pipeline {
    agent any
    stages {
        stage('Build Backend'){
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Unit Tests'){
             steps {
                 sh 'mvn test'
             }
        }
    }
}