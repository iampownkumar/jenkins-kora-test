pipeline {
    agent any
    stages {
        stage('Hello from GitHub') {
            steps {
                echo 'Jenkins triggered from GitHub push!'
                sh 'whoami'
                sh 'date'
                echo 'if you are seing this message means that our github commit and auto develope is successful '
                echo 'my mistake i typed sh first instead of echo and now i think it will work like a charm'
            }
        }
    }
}
