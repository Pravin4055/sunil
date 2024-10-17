pipeline {
    agent any 
    
    stages {
        stage('Clone Repository') {
            steps {
                // This step is automatically handled by Jenkins when using SCM
                echo 'Cloning the repository...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Run the Python script
                sh 'python3 app.py'
            }
        }
    }
}

