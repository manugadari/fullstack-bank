pipeline {
    agent any

    stages {
    
        stage('Git checkout') {
            steps {
                git 'https://github.com/manugadari/fullstack-bank'
                sh'git diff master--feature'
            }
         }
    }
}
