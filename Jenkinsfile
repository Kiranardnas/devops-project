pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                echo 'Running Python Script...'
                bat 'dir'
                bat 'python app.py'
            }
        }
    }
}
