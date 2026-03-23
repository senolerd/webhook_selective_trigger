pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                script{
                    echo "========executing A========"
                    echo "GIT commiter name: ${GIT_COMMITTER_NAME}"
                }
            }
        }
    }
}