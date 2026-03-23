pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                script{
                    echo "=======ENV ======= }"
                    sh "env" 
                    echo "checking if ignore is working. Email set to: mahmut@mahmut.com"
                }
            }
        }
    }
}