pipeline{
    agent any
    stages {
        stage('Build') {
            steps{
                echo 'This is a build step' 
            }
        }
        stage('Test') {
            steps{
                echo 'This is a test step' 
                sleep(600)
            }
        }
        stage('Deploy') {
            steps{
                echo 'This is a deploy step'    
            }
        }
    }
}
