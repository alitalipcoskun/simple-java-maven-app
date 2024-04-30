pipeline{
    agent any
    tools{
        mvn 'Maven 3.0.5'
    }
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