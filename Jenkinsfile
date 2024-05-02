pipeline{
    agent any
    stages{
        stage('Build'){
            environment {
                PATH = "/home/jenkins/apache-maven-3.8.6/bin"
                }
            steps{
                sh '''
                    mvn --version
                '''
            }
        }
    }
}