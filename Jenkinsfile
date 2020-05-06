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
                sleep(15)
            }
        }
        stage('Deploy') {
            steps{
                ech 'This is a deploy step'    
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
