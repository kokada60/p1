pipeline {
    agent any
    stages {
        stage("Stage 1") {
            steps {
                sh "echo 'Hello Worlds!!!'"
            }
        }
        stage("Building...") {
            steps {
                sh "echo 'Building'"
            }
        }
        stage("Test") {
            steps {
                sh "echo 'Hi Im testing'"
            }
        }
        stage("Deploy") {
            steps {
                echo "Im deploying..."
            }
        }
    }
}