pipeline{
    agent any
    stages{
        stage('Build'){
            tools{
                maven 'MAVEN_HOME'
                jdk 'JAVA_HOME'
            }
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