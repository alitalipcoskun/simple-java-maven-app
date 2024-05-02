pipeline{
    agent any
    stages{
        stage('Build'){
            tools{
                maven 'MAVEN_HOME'
                jdk 'JAVA_HOME'
            }
            steps{
                sh '''
                    mvn --version
                '''
            }
        }
    }
}