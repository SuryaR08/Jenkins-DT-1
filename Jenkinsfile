pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/your-username/cpp-hello-world.git'
            }
        }
        stage('Build') {
            steps {
                bat 'make'
                bat 'hello.exe'
            }
        }
    }
}
