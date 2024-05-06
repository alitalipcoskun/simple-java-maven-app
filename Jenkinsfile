pipeline{
    agent any
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