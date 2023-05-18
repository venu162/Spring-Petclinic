pipeline{
    agent {label 'OPENJDK-17'}
    stages{
        stage('continousdownload'){
            steps{
                git 'https://github.com/spring-projects/spring-petclinic.git'
            }
        }
    }
}