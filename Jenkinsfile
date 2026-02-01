pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/GADDAM-SHARMILA/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building project..."
            }
        }

        stage('Run') {
            steps {
                echo "Running Hello World..."
                python app.py
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
