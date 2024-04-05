pipeline {
    agent any

    tools {
        jdk 'JDK11'
        git 'Default'
    }

    stages {
        stage('Compile') {
            steps {
                sh 'javac Jenkins.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Jenkins'
            }
        }
    }
}
