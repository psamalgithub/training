pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'cd /tmp'
                sh 'pwd'
                sh 'touch temp.txt'
                sh 'ls -lrt'
                sh 'cp temp.txt temp1.txt'
                sh 'ls -lrt'
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
