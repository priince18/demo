pipeline{
    agent any
    stages{
        stage('Building'){
            steps{
                echo 'the code will now be build into an artifact'
            }
        }
        stage('Artifact Archiving'){
            steps{
                echo 'the Artifact will be uploaded to an artifact repository'
            }
        }
        stage('testing'){
            steps{
                echo 'the artifact will be tested'
            }
        }
        stage('Staging'){
            steps{
                echo 'the artifact is staged onto the staging server'
            }
        }
        stage('Deploy'){
            steps{
                echo 'the software will now be deployed!'
            }
        }
    }
}
