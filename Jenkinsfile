pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'buliding'
                sh 'sudo apt update'
                sh 'sudo apt-get install nodejs -y'
                sh 'npm install'
                sh 'npm start & sleep 60'
            }
        }
    }
}
