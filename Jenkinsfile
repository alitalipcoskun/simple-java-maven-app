pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh '''
                    echo build
                   '''
                sh '''
                mvn -B -DskipTests clean package
                '''
            }
        }
    }
}