pipeline {
    agent {
        node {
            label 'slave2'
        }
    }
    tools {
        maven 'maven3'
    }
    stages {
        stage('checkout') {
            steps{
                git 'https://github.com/akhilesh9014/Maven-Java-Project.git'
            }
        }
    }
}  
