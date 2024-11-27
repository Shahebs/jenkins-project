pipeline {
    agent any
    stages {

        stage('Checkout') {
            steps {
                git url: 'https://github.com/Shahebs/jenkins-project.git', branch: 'main'
                sh "ls -ltr"
            }
        }
        stage('Test1') {
            steps {
                sh "whoami"
            }
        }

     }
}
