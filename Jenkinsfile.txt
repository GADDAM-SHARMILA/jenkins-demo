pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'echo Hello World from Jenkins Pipeline!'
            }
        }
    }
}
