pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'I am in Dev'
                sh 'git --version'
            }
        }
    stage('prod') {
            steps {
                sh 'python3 helloworld.py'
            }
        }
    }
}
