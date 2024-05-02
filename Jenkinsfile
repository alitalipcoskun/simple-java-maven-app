pipeline{
    agent any
    environment{
        EXAMPLE_CRED = credentials('first_secret_text')
    }
    stages{
        stage('Build'){
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