pipeline{
    agent any

    stages('hostname'){
        steps{
            sh 'hostname'
        }
    }
    stages('ip-add'){
        steps{
            sh 'hostane -I'
        }
    }
    stages('cpu-details'){
        steps{
            sh 'lscpu'
        }
    }
    stages(mem-usage){
        steps{
            sh 'free -h'
        }
    }
    stages(disk-uasge){
        steps{
            sh 'df -h'
        }
    }
    stages('date'){
        steps{
            sh 'date'
        }
    }
}
