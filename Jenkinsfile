pipeline {
    agent {
        any { image 'maven:3.9.6-sapmachine-21' }
    }

    stages {
        stage('Build') {
            steps{
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
