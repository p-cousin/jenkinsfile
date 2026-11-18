pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Construction...'
            }
        }
        stage('Test') {
            steps {
                echo 'Lancement des tests...'
                // Cette commande fait volontairement échouer le pipeline
                error 'Échec volontaire lors des tests !' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Déploiement en production'
            }
        }
    }
}
