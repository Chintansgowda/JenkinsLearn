pipeline {
    agent {
        label 'slave'
    }

    stages {
        stage('hostname') {
            steps {
                sh 'hostname'
            }
        }
        stage('ip-add') {
            steps {
                sh 'hostname -I'
            }
        }
        stage('cpu-details') {
            steps {
                sh 'lscpu'
            }
        }
        stage('mem-usage') {
            steps {
                sh 'free -h'
            }
        }
        stage('disk-usage') {
            steps {
                sh 'df -h'
            }
        }
        stage('date') {
            steps {
                sh 'date'
            }
        }
    }
}
