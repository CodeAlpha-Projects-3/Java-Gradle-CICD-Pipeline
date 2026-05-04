pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Code download
                checkout scm
            }
        }

        stage('Build & Test') {
            steps {
                // Gradle
                sh './gradlew build'
            }
        }

        stage('Archive Artifacts') {
            steps {
                // Build 
                archiveArtifacts artifacts: 'app/build/libs/*.jar', allowEmptyArchive: true
            }
        }
    }
}
