pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning repo...'
                git branch: 'main', url: 'https://github.com/Kandregulakishore/CICDPIPELINE.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Build stage - success ✅'
            }
        }
    }
}
