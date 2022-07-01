pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/salyx21/flask-demo.git'

                // Run env.
                sh "python -m venv .venv"

                //Run pip install
                sh "pip install -r requirements-dev.txt"
                
            }
        }
    }
}
