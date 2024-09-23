pipeline {
    agent any
    tools {
        maven 'Maven 3.9.9'
    }
    stages {
        stage('Karate Test Stage') {
            steps {
                sh label: 'Run Karate Tests', script: "mvn test"
            }
        }
    }
}
