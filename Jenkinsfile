pipeline{
    agent any
    stages{
        stage('Build'){
            environment {
                PATH = "/home/jenkins/apache-maven-3.8.6/bin:${env.PATH}"
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