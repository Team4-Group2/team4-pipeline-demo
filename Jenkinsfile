pipeline{
    agent any
    stages{
        stage('1-repoClone'){
            steps{
                sh 'df -h'
            }
        }
        stage('2-cpuAnalysis'){
            steps{
                sh 'lscpu'
            }
        }
        stage('3-memoryCheck'){
            step{
                sh 'free -g'
            }
        }
        stage('4-osStats'){
            step{
                sh 'cat /etc/os-release'
            }
        }
    }
}