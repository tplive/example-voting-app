pipeline {
    agent any

    stages{
        stage("one"){
            steps{
                echo 'step 1'
            }
        }
        stage("two"){
            steps{
                echo 'step 2'
            }
        }
        stage("three"){
            steps{
                echo 'steps 3'
            }
        }
    }

    post{
        always{
            echo 'This pipeline is completed..'
        }
    }
}