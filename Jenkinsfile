pipeline {
agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/adiyosef/jenkins_test.git'
            }
        }
        stage('build') {
            steps {
                sh 'python 1.py'
            }
       
        }
    }
}
