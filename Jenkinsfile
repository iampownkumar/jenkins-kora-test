pipeline {
    agent any
    stages {
        stage('Hello from GitHub') {
            steps {
                echo 'Jenkins triggered from GitHub push!'
                sh 'whoami'
                sh 'date'
            }
        }
    }
}
