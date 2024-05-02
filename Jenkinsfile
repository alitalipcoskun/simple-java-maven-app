pipeline{
    agent any
    stages{
        stage('Build'){
            environment {
                PATH = "/home/jenkins/apache-maven-3.8.6/bin:${env.PATH}"
                JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.412.b08-1.el7_9.x86_64/jre"
                MAVEN_HOME = "/home/jenkins/apache-maven-3.8.6/" 
                }
            steps{
                script{
                    sh '''
                    export PATH="/home/jenkins/apache-maven-3.8.6/bin:$PATH"; 
                    mvn --version
                    '''
                }
            }
        }
    }
}