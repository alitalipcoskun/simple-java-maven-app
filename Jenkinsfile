pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh '''
                    echo build
                    pwd
                    mvn --version
                   '''
            }
        }
    }
}