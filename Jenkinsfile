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
        stage('Test'){
            steps{
                sh '''
                echo Test
                '''
            }
        }
        stage('Push'){
            steps{
                sh '''
                echo Push
                '''
            }
        }
        stage('Deploy'){
            steps{
                sh '''
                echo Deploy
                '''
            }
        }
    }
}