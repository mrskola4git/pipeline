pipeline {
    agent any 
    { 
        docker { image 'node:14-alpine' } 
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
