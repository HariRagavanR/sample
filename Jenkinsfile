pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/HariRagavanR/sample.git'
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'ls -la'
                sh 'python3 file.py'
            }
        }
    }
}
