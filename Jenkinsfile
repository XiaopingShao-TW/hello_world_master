pipeline{
    agent any
    stages {
        stage('Build') {
            steps{
                echo 'This is a buildddd step' 
            }
        }
        stage('Test') {
            steps{
                echo 'This is a test step' 
                sleep(20)
            }
        }
        stage('Deploy') {
            steps{
                echo 'This is a deploy step'    
            }
        }
    }
}