pipeline {
    agent any
    environment {
        ACCESS_KEY_ID     = credentials('MyTest123')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo ACCESS_KEY_ID_USR
                echo ACCESS_KEY_ID_PSW
            }
        }
        stage('Test') {
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
