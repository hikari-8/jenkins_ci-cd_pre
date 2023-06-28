pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                python -v
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}


// テストコード
    // stages {
    //     stage('Test') {
    //         steps {
    //             checkout scm
    //             sh 'python -m unittest discover .'
    //         }
    //     }
    // }