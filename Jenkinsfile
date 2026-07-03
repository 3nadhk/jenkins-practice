pipeline {
    agent {
        label 'AGENT-1'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..the build in Jen'  
            }
        }
        stage('Test') {
            steps { 
                echo 'Testing progress..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to the app....'
            }
        }
    }
}