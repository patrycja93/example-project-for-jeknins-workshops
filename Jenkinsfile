pipeline {
    agent any

    tools {
        maven 'maven'
    }

    stages {
        stage('env info') {
            steps {
                bat 'java --version'
            }
        }
        stage('build') {
            steps {
                bat 'mvn compile'
            }
            steps {
                bat 'mvn package'
            }
        }
    }
}
