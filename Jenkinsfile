pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               sh 'cd coit-backend1 && mvn install'
            }
        }
        stage('docker-build') {
            steps {
               sh 'echo "Docker Build"'
               // sh 'cd coit-backend1 && docker build -t amol1996/coit-backend1-92234832:v2 .'
               // sh 'docker images' 
            }
        }
        stage('docker-push') {
            steps {
                sh 'echo "Docker Push"'
                // sh 'echo "pushing docker image"'
                // sh 'docker push amol1996/coit-backend1-92234832:v2'
            }
    }
}
}
