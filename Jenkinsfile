pipeline{
    agent any
        tools {
        maven 'maven-3.8.6'
    }
    stages{
        stage('Build'){
            steps{
                script{
                    sh ''' 
                    mvn --version
                    '''
                }
            }
        }
    }
}