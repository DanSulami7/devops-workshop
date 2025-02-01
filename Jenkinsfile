pipeline {
    agent { label 'maven' } 

    environment {
        PATH = "/opt/apache-maven-3.9.9/bin:$PATH"
    }

    stages {
        stage('Build') { 
            steps {
                sh 'export PATH=/opt/apache-maven-3.9.9/bin:$PATH && mvn clean deploy'
            }
        }
    }
}
