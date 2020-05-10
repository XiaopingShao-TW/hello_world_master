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
                sleep(3000)
                /*master的改动*/
            }
        }
        stage('Deploy') {
            steps{
                echo 'This is a deploy step'    
            }
        }
    }
    post {
        success {
            echo 'Here we kickoff run job test'
            build job: 'test'                                                                
               
            }
    }
}
