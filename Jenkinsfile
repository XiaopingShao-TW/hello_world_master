pipeline{
    agent any
    stages {
        stage('Build') {
            steps{
                ech 'This is a build step' 
            }
        }
        stage('Test') {
                input {
                message "Should we continue?"
                ok "Yes, we should."
            }
            steps{
                echo 'This is a test step' 
                sleep(5)
            }
        }
        stage('Deploy') {
            steps{
                echo 'This is a deploy step'    
            }
        }
    }
}
