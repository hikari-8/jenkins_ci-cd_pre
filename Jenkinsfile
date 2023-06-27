pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                checkout scm // リポジトリからソースコードをチェックアウトします
                sh 'python -m unittest discover .' // テストを実行します
            }
        }
    }
}
