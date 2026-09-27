pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out DBST-101 code...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Customer 5G Plan Activation Validation...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running DBST-101 tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment simulation completed.'
            }
        }
    }

    post {
        success {
            echo 'DBST-101 pipeline completed successfully.'
        }

        failure {
            echo 'DBST-101 pipeline failed.'
        }
    }
}
