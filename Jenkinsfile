pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Conectando con GitHub y descargando código...'
            }
        }
        stage('Build') {
            steps {
                echo 'Construyendo la aplicación...'
            }
        }
        stage('Test & Deploy') {
            steps {
                echo 'Ejecutando tests... ¡Todo correcto! Desplegando...'
            }
        }
    }
}
