pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh " sh 2.sh "
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
