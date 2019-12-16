pipeline {

       agent { label 'java-build' }
       tools {
	
	maven "M2_HOME"
        jdk "java8"
	       
        stages {
		stage("Build using maven") {
 		    steps {
                      echo "am building using maven"
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
}
