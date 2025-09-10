pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch: 'main', credentialsId: '3a8764ee-cb4e-47af-92ea-053a9d4c7492', url: 'https://github.com/arshsolkar/javafile.git'
            }
        }
      stages {
        stage('compile') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }
        stages {
        stage('run') {
            steps {
                bat 'java HelloWorld' 
            }
        }
    }
}
