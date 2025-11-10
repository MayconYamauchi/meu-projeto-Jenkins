pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Construindo o projeto...'
                // Exemplo: sh 'mvn clean install' ou 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Executando testes...'
                // Exemplo: sh 'npm test' ou 'pytest'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Realizando deploy...'
                // Exemplo: sh './deploy.sh'
            }
        }
    }

    post {
        success {
            echo 'Pipeline concluído com sucesso!'
        }
        failure {
            echo 'Pipeline falhou!'
        }
    }
}
