pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                script {
                    bat 'C:\\Windows\\System32\\cmd.exe /c docker build -t my-kube1 .'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    echo 'Running tests...'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying application...'
                }
            }
        }
    }
}
