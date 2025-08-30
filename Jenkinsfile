
pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/Kandregulakishore/CICDPIPELINE.git'
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'pip3 install -r requirements.txt || echo "No requirements.txt found"'
            }
        }
        stage('Run App') {
            steps {
                sh 'python3 app.py || echo "No app.py found"'
            }
        }
    }
}
