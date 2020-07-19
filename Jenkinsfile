pipeline {
    agent any

    stages {
        stage('Verified Branch') {
            steps {
                echo $GIT_BRANCH
            }
            post{
                success{
                    echo "Stage1 Su :)"
                }
                failure{
                    echo "Stage1 Failed :("
                }
            }
        }       
    }
}
