pipeline{
    agent any

    stages {
        stege('checkout scm'){
            steps{
                echo 'pulling code from repo'
            }
        }
        stage('build'){
            step{
                echo 'building project using maven'
            }
        }
    }
}
