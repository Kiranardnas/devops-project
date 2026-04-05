pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                bat '''
                echo Running Python Script...
                dir
                python app.py
                '''
            }
        }
    }
}
