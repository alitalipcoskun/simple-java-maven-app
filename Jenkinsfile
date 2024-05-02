pipeline{
    agent any
    environment{
        EXAMPLE_CRED = credentials('first_secret_text')
    }
    stages{
        stage('Build'){
            tools{
                maven MAVEN_HOME
                jdk JAVA_HOME
            }
            steps{
                sh '''
                    echo build
                    echo ${EXAMPLE_CRED}
                    pwd
                    mvn --version
                   '''
            }
        }
    }
}