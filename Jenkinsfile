pipeline{
    agent any
    environment{
        APPLIUCATION_NAME = 'Petrol pump'
    }

    stages {
        stage ('checkout scm'){
            steps{
                echo "pulling code from repo${APPLIUCATION_NAME}"
            }
        }
        stage ('build'){
            steps{
                echo 'building project using maven'
            }
        }
        stage ('global variavles'){
            steps{
                echo "${env.BUILD_NUMBER}"
                echo "${env.JOB_TYPE}"
            }
        }
    }
}
