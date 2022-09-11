pipeline {
    agent any

    stages {
        stage('Vesrion') {
            steps {
                sh 'python --version'
            }
        }
        stage('run1') {
            steps {
                sh 'web_scrapper.py'
            }
        }
    }
}
