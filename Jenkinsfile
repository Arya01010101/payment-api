
pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo "Source code checkout started"
            }
        }

        stage('build') {
            steps {
                script {
                    def application_name = "payment-api"
                    echo "Application_name: ${application_name}"
                    echo "Build stage started"
                }
            }
        }

        stage('test') {
            steps {
                echo "Application testing started"
            }
        }

        stage('deploy') {
            steps {
                echo "Deployment requires approval"
                echo "please give approval man"
            }
        }
    }
}
