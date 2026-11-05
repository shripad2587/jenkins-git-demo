pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checkout Stage Started'
                sh '''
                pwd
                ls -lrt
                sleep 5
                '''
            }
        }

        stage('Build') {
            steps {
                echo 'Build Stage Started'
                sh '''
                echo "Building Application"
                sleep 5
                '''
            }
        }

        stage('Test') {
            steps {
                echo 'Test Stage Started'
                sh '''
                echo "Testing Application"
                sleep 10
                '''
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy Stage Started'
                sh '''
                echo "Deploying Application"
                sleep 10
                '''
            }
        }
        stage('Hefshine') {
            steps {
                echo 'Hefshine'
                sh '''
                echo "  Hefshine"
                sleep 3
                '''
            }
        }
               stage('Happy Diwali') {
            steps {
                echo 'Happy Diwali'
                sh '''
                echo "Happy Diwali"
                sleep 3
                '''
            }
        }
    }

    post {
        success {
            echo 'Pipeline Executed Successfully'
        }

        failure {
            echo 'Pipeline Failed'
        }
    }
}