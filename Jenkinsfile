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
                sh 'python3 web_scrapper.py'
            }
        }
    }
}
