pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/marcus1708/CursoJenkins.git'
            }
        }

        stage('Mostrar conteúdo do arquivo') {
            steps {
                sh 'ls -la'
                sh 'cat *.txt'
            }
        }
    }
}
