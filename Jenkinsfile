pipeline{
    agent any
    environment{
        EXAMPLE_CRED = credentials('first_secret_text')
    }
    stages{
        stage('Build'){
            tools{
                maven 'mvn 3.0.5'
                jdk 'jdk-1.8.0'
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