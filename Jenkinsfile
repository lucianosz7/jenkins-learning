pipeline {
    agent any
    tools {
        go 'go-1.16.6'
    }
    enviroment {
        GO111MODULE = 'on'
    }
    options {
        skipStagesAfterUnstable()
    }

    stages {
        stage('Build') {
            steps {
                echo "Building Project"
                sh 'go build'
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