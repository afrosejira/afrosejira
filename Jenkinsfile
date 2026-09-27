pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out DBST-62 code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Customer Profile API'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests for DBST-62'
            }
        }

        stage('Integration Test') {
            steps {
                echo 'Jira DBST-62 Jenkins integration test'
            }
        }
    }

    post {
        success {
            echo 'DBST-62 Jenkins build SUCCESS'
        }

        failure {
            echo 'DBST-62 Jenkins build FAILED'
        }
    }
}
