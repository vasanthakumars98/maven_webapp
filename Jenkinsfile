pipeline {

       agent { label 'java-build' }
              
       stages{
		stage("Build using maven") {
 		    steps {
                      echo "am building using maven"
		      sh 'ls -ltr'
		      sh 'mvn install'
		}

	}

	        stage("Results") {
                     steps {
    		      echo "this is a test stage"
		
		}
	}
	}
       
}
