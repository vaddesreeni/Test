pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo "Size ${params.size}"
            }
        }
        stage('deploy') {
            steps {
                echo "Color ${params.color}"
            }
        }
        stage('build-test') {
            steps {
                sh "docker --version"
                echo "test:color"
            }
        }
    }
}
