pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                script{
                    sh ''' 
                    echo $M2_HOME
                    echo $PATH
                    mvn clean install
                    '''
                }
            }
        }
    }
}