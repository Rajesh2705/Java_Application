pipeline {
    agent any
    stages {
        stage('Build Application') {
            steps {
                sh 'javac Sample.java'
            }
        }
        stage('Run Application'){
            steps{
               sh 'java Sample'
            }  
        }
    }
}