pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                script{
                    echo "========executing A========"
                    echo "GIT commit id: ${GIT_COMMIT}"
                }
            }
        }
    }
}