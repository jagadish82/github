pipeline{
    agent any
    
    stages{
        stage('Hostname'){
            steps{
                sh "hostname"
            }
        }
        stage('Server IP'){
            steps{
                sh "hostname -I"
            }
        }
        stage('Disk Usage'){
            steps{
                sh "df -h"
            }
        }
        stage('Server up Time'){
            steps{
                sh "uptime"
            }
        }
        stage('Memory Usage'){
            steps{
                sh "free -h"
            }
        } 
    }
}
