pipeline{
    agent any
    enviornment{
        APPLIUCATION_NAME = "Petrol pump"
    }

    stages {
        stage ('checkout scm'){
            steps{
                echo "pulling code from repo'${APPLIUCATION_NAME}"
            }
        }
        stage ('build'){
            steps{
                echo 'building project using maven'
            }
        }
    }
}
