pipeline {
    agent {
       node{
           label 'maven'
       } 
    } 
    stages {
        stage('Clone-core') {
            steps {
                git branch: 'main', url: 'https://github.com/ravdy/tweet-trend-new.git'
            }
        }
    }
}