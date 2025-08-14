pipeline {
    agent any

    stages {
        stage("Hostname") {
            steps {
                sh 'hostname'
            }
        }

        stage("IP-adds") {
            steps {
                sh 'hostname -I'
            }
        }

        stage("CPU-Details") {
            steps {
                sh 'lscpu'
            }
        }

        stage("Mem-usage") {
            steps {
                sh 'free -h'
            }
        }

        stage("Disk-Usage") {
            steps {
                sh 'df -h'
            }
        }

        stage("date") {
            steps {
                sh 'date'
            }
        }

        stage("Running Process"){
            steps {
                sh 'ps aux'
            }
        }    
    }
}
