pipeline {
	agent any 
	environment {
	  JAVA_VERSION = "11.0"
	  JAVA_PATH = "/usr/sbin/java"
	}

	stages {
		stage("working with variables") {
			steps {
				script {
					var1=10
					var2="dvs technologies"
					println "myvar1 value is ${var1} and myvar2 value is ${var2}"
					println "my workspace is ${WORKSPACE}"
					println "my build no is ${BUILD_NUMBER}"
					println "my java version is ${env.JAVA_VERSION}"
					println "my java path is ${env.JAVA_PATH}"
				}
			}
		}
	}
}
