pipeline {

       agent { label 'java-build' }
       tools {
	
	maven "M2_HOME"
        jdk "java8"

	}
	stages{
   	stage("Cloning frm git") {
		steps {
		 echo "am cloing frm git"  
	         git credentialsId: '631ec87d-9500-49f8-a051-f8ae78c22d16', url: 'https://github.com/vasanthakumars98/vasanth.git'
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
}
