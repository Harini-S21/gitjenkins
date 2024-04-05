pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac Jenkins.java'
            }
        }
        stage('Run') {
                sh 'java Jenkins'
            }
        }
    }
}
