pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'buliding'
                sh 'sudo apt update'
                sh 'sudo apt-get install nodejs'
                sh 'sudo npm install npm@latest -g'
                sh 'npm start & sleep 60'
            }
        }
    }
}
