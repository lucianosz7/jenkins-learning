pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }

    stages {
        stage('Build') {
            steps {
                echo "Building Project"
            }
        }
        stage('Test') {
            steps {
                echo "Testing Project"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying Project"
            }
        }
    }
}