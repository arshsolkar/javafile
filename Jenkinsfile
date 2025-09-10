pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                echo 'Hello World'
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
