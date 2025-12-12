pipeline {
    agent any

    stages {
        stage('Check Python Version') {
            steps {
                bat 'python --version'
            }
        }
        stage('Run Script') {
            steps {
                bat 'python myscript.py'
            }
        }
    }
}
