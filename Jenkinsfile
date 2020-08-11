pipeline {
    agent any
    environment {
        ACCESS_KEY_ID     = credentials('MyTest')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo ACCESS_KEY_ID_USR
                echo ACCESS_KEY_ID_PWD
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
