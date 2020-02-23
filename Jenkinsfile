pipeline {
   agent any

   tools {
      maven 'maven3.6.3'
   }
   
   stages {
      
      stage('build code') {
         steps {
            echo 'build code'
			sh "mvn -version"
			sh "mvn -X"
			sh "printenv"
         }
      }
	  
   }
}