pipeline{
    agent any
    stages{
        stage("Git Checkout new trigger"){
            steps{
                echo "Repository checked out successfully."
                sh 'pwd'
                sh 'ls -lrt'
                echo "Tested Checkout moving to net step"
            }
        }
    }
}
