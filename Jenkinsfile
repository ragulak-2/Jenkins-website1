pipeline {
    agent any

    stages {
        stage('Deploy Site1') {
            steps {
                sh '''
                sudo rm -rf /var/www/site1/*
                sudo cp -r Carwebsite-Static-FE/* /var/www/site1/
                '''
            }
        }
    }
}
