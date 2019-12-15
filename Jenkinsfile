pipeline {

       agent { label 'java-build' }
       tools {
	
	maven "M2_HOME"
        //jdk "java8"
        env.JAVA_HOME = "/usr/bin/java"
	sh "/usr/bin/java -version"
	sh '$JAVA_HOME/usr/bin/java -version'
	}
	stages{
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
