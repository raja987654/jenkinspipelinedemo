pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Marhba bik fil Jenkins Pipeline!'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Na3mlou build lil projet...'
                // Hne normalement t7ott el commands mta3 el build
            }
        }
        
        stage('Test') {
            steps {
                echo 'Na3mlou el tests...'
                // Hne normalement t7ott el commands mta3 el tests
            }
        }
    }
    
    post {
        success {
            echo 'El pipeline naja7 b kol khir!'
        }
        failure {
            echo 'Oups! Famma 7aja ma mchetch mrigla.'
        }
    }
}
