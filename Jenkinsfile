pipeline {
    agent any
    stages {
        stage('Build Application') {
            steps {
                sh 'javac Simple.java'
            }
        }
        stage('Run Application'){
            steps{
               sh 'java Simple'
            }  
        }
    }
}