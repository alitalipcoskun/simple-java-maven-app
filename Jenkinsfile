pipeline{
    agent any
    tools{
        maven 'Maven 3.0.5'
        jdk 'jdk8'
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