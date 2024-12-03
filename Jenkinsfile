pipeline {
    agent {
        label 'test-agent'
    }
    stages {
        stage('Build') {
            steps {
                // Run the Gradle build command
                sh './gradlew clean build'
            }
        }
    }
}