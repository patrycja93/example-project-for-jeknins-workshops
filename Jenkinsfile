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
        stage('build') {
            steps {
                sh 'mvn compile'
            }
            steps {
                sh 'mvn package'
            }
         }
    }
}
