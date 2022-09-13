pipeline {
    agent any

    stages {
        stage('Prebuild') {
            steps {
                echo 'Building..'
                ls
                npm run build
            }
        }
        stage('Build') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}