pipeline {
    agent any

    stages {
        stage('Merge') {
            steps {
                git branch: 'main', url: 'https://github.com/mishkak/Home-assignment-Aurora-Labs-by-Michael.git'
            }
        }
        stage('Build') {
            steps {
                sh '/usr/bin/python3 main.py'
            }
        }
    }
}
