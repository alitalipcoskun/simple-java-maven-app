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
                    echo $M2_HOME
                    echo $PATH
                    mvn clean install
                    '''
                }
            }
        }
    }
}