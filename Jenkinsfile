pipeline {
    agent any

    tools {
        maven 'maven'
    }

    stages {
        stage('env info') {
            steps {
                sh 'java --version'
            }
        }
    }
}
