pipeline {

    agent any


    stages {


        stage('Build') {

            steps {

                echo "Building Application"

                sh 'npm run build'

            }
        }


        stage('Test') {

            steps {

                echo "Testing Application"

                sh 'npm test'

            }
        }


        stage('Deploy') {

            steps {

                echo "Deploying Application"

            }
        }

    }


    post {

        success {

            echo "Pipeline Successful"

        }


        failure {

            echo "Pipeline Failed"

        }

    }

}