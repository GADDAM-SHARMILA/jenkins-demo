pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull code from GitHub (optional)
                git branch: 'main', 
                    url: 'https://github.com/GADDAM-SHARMILA/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                // Simulate build by printing message
                bat 'echo Hello World - Build Stage'
            }
        }

        stage('Test') {
            steps {
                // Simulate test by printing message
                bat 'echo Hello World - Test Stage'
            }
        }

        stage('Deploy') {
            steps {
                // Simulate deploy by printing message
                bat 'echo Hello World - Deploy Stage'
            }
        }
    }
}
