pipeline {
    agent {
        docker {
            image 'node:16' // Use Node 16 Docker image as the build agent
        }
    }
    stages {
        stage('Build') {
            steps {
                checkout scm
                sh 'npm install --save' // Run npm install command
            }
        }
    }
    post {
        success{}
        failure{}
    }
}

