pipeline {
    agent any 
    stages {
        stage ('Build Backend') {
            steps {
                bat 'mvb clean package -DskipTests=true'
            }
        }
    }
}