pipeline{
	agent any
	environment {

    		PATH = "C:\\WINDOWS\\SYSTEM32:C:\\Program Files\\Java\\jdk1.8.0_211\\bin"

	}
	stages{
		stage('build'){
			steps{
				echo "First Program"
				bat "javac HelloWorld.java"
			}
		}
	}
} 
