pipeline {  

    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Code Cloned Successfully'
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo 'Build Started'
                sh 'echo Building Application'
                echo 'Build Successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Application'
                sh 'echo Test Completed Successfully'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment Started'
                sh 'echo Application Deployed Successfully'
            }
        }

    }

    post {

        success {
            echo 'Pipeline Completed Successfully'
        }

        failure {
            echo 'Pipeline Failed'
        }

    }
}
