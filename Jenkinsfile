pipeline {
    agent any

    stages {
       
        stage('run1') {
            steps {
                sh 'web_scrapper.py'
            }
        }
        stage('echo') {
            steps {
                sh 'echo $PATH'
            }
        }
    }
}
