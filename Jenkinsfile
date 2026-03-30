pipeline {
    agent any
    stages {
        stage('Hello from GitHub') {
            steps {
                echo 'Jenkins triggered from GitHub push!'
                sh 'whoami'
                sh 'date'
                sh 'if you are seing this message means that our github commit and auto develope is successful '
            }
        }
    }
}
