pipeline {
    agent {
        docker {
            image 'node:16' // Use Node 16 Docker image as the build agent
            args '-u root' // Run Docker container as root (optional)
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install --save' // Run npm install command
            }
        }
    }
}

