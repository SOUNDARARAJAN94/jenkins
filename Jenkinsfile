pipeline {

    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Code Cloned Successfully'
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo 'Build Started'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Completed'
            }
        }

        stage('Deploy') {
            steps {

                echo 'Deployment Started'

                sh '''
                cp soundar.txt /usr/share/nginx/html/
                '''

                echo 'Deployment Completed'
            }
        }
    }
}
