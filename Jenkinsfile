pipeline {
    agent any

    stages {
        stage('SCM') {
            steps {
                // Realiza la operación de checkout del código fuente
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // Aquí puedes añadir los pasos para construir tu aplicación
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                // Aquí puedes añadir los pasos para probar tu aplicación
                echo 'Testing...'
            }
        }

        stage('Deploy') {
            steps {
                // Aquí puedes añadir los pasos para desplegar tu aplicación
                echo 'Deploying...'
            }
        }
    }
}
