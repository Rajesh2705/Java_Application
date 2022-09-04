pipeline {
    agent any
    stages {
        stage('Build Java and run application') {
            steps {
                sh 'javac Sample.java'
            }
            steps{
                sh 'java Sample'
            }
        }
    }
}
