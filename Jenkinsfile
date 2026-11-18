pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build réussi'
            }
        }
        stage('Test') {
            steps {
                echo 'Lancement du test qui va échouer...'
                sh 'exit 1'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Déploiement terminé'
            }
        }
    }
}
