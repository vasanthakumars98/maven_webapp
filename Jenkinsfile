pipeline {

       agent { label 'java-build' }
       tools {
	
	maven "M2_HOME"
        jdk "java8"

	}

   	stage("Cloning frm git") {
		steps {
		 echo "am cloing frm git"                
		}

	}

	stage("Build using Maven") {
 		steps {
                 echo "am building using maven"
		}

	}

	stage("Results") {
               steps {
    		echo "this is a test stage"
		
		}
	}
}
