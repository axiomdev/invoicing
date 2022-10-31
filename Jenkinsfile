pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd /var/www/'
                sh 'pwd'
                echo "je suis ici"
                sh "touch test.txt"
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
