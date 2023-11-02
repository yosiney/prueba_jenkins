pipeline {
    agent any

    stages {
        stage('Get Anime Titles') {
            steps {
                
                sh "python -c Consumer_api.py"
            
            }
        }
    }
}

