pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script{
                    sh 'echo "Building a docker file"'
                }
            }
        }
        stage('docker push') {
            steps {
                script{
                    sh 'echo "pushing a docker"'
                }
            }
        }
    }
}