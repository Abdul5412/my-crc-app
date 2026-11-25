pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Application code checkout successful'
            }
        }

        stage('Build') {
            steps {
                echo 'Building My CRC Application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application to MicroShift'
            }
        }
    }
}
