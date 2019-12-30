pipeline {
         agent any
	 tools {
        maven 'maven'
            }	
         stages {
                 stage('One') {
                 steps {
                     echo 'We are in stage One'
						}
                 }
				 stage('Two') {
                 steps {
                     echo 'Hi, We are in stage Two'
						}
                 }
				 stage('Three') {
                 steps {
                     echo 'Hi, We are in stage Three'
					 
					 bat 'mvn -Dsurefire.useFile=false test'
						}
                 }
                 
				}
}
