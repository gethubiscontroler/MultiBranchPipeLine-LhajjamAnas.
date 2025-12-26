pipeline {
    agent any

    stages {
        stage('Compilation') {
            steps {
                echo 'Lancement de la compilation Maven...'
                sh 'mvn clean compile'
            }
        }
        stage('Tests') {
            steps {
                echo 'Lancement des tests unitaires...'
                sh 'mvn test'
            }
        }
    }
}
