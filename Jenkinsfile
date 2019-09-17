def mvnHome
pipeline {
   agent any
   stages {
       stage('Code from GitHub') {
	        steps {
			    git 'https://github.com/ravikiran529/Maven-Java-Project.git'
				script{
			        mvnHome = tool 'maven3.6'
			    }
			}
	   }
   } 
}     
