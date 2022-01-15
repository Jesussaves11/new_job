pipeline {
    agent  {
        docker { image 'node:16.13.1-alpine' }
    }
    tools{
        jdk "Java8"
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}