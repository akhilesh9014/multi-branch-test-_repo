pipeline {
	agent  {
		label 'slave2'
	}	
   stages {
       stage('Code from GitHub') {
	        steps {
			    git 'https://github.com/ravikiran529/Maven-Java-Project.git'
			    echo "build success"
	        }
       }
   } 
}     
