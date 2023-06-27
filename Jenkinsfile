pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                checkout scm
                sh 'python -m unittest discover .'
            }
        }
    }
}
