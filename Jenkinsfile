pipeline {
    agent any

    stages {
        stage('Compilation') {
            steps {
                echo 'Lancement de la compilation Maven...'
                bat 'mvn clean compile'
            }
        }
        stage('Tests') {
            steps {
                echo 'Lancement des tests unitaires...'
                bat 'mvn test'
            }
        }
    }
}