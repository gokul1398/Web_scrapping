pipeline {
    agent any

    stages {
         stage('Vesrion') {
            steps {
                sh 'python --versioudo apt install python3.8n'
            }
        }
        stage('run1') {
            steps {
                sh 'python3.8 web_scrapper.py'
            }
        }
    }
}
