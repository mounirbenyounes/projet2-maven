pipeline {
         agent any
		 tools {
        maven 'Maven 3.3.9'
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
					mvn compile
						}
                 }
                 
				}
}
