pipeline {
    agent any

    stages {
        stage('test-pr') {
            steps {
                checkout scm
                sh 'python -m unittest discover .'
            }
        }
    }
}
