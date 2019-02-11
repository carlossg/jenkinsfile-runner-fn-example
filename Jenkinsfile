pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'git clone https://github.com/carlossg/jenkinsfile-runner-fn-example.git'
                echo 'Hello world!'
                sh 'mvn clean package'
            }
        }
    }
}
