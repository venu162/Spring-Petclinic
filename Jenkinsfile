pipeline{
    agnet {label 'OPENJDK-17'}
    stgaes{
        stage('continousdownload'){
            steps{
                git 'https://github.com/spring-projects/spring-petclinic.git'
            }
        }
    }
}