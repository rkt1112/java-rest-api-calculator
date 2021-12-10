pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/rkt1112/java-rest-api-calculator.git'
                sh './mvnw clean compile'
                // bat '.\\mvnw clean compile'
            }
        }
    }
}
