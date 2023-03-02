pipeline {
    agent {
        docker{
            image 'maven:latest'
        }
    }

    stages {
        stage('Design') {
            steps {
                echo 'Design'
            }
        }
        stage(Implement){
            steps{
                echo "Implement"
            }
        }
        stage(Test){
            steps{
                echo 'Test'
            }
        }
        stage(Deploy){
            steps{
                echo 'Deploy'
            }
        }
    }
}
