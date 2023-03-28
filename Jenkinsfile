//Scripted
// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// 	stage('Integration Test') {
// 		echo "Test"
// 	}
// }

//Declarative
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build Stage Success"
			}
		}
		stage('Test') {
			steps {
				echo "Test Stage Success"
			}
		}
		stage('Functional') {
			steps {
				echo "Functional Test Stage Success"
			}
		}
	}
	post {
		always {
			echo "Awsome, this message will always appear in the consol log"
		}
		success {
			echo ":-) This message will appear only after SUCCESS"
		}
		failure {
			echo ":- ( This message will appear only after Failure"
		}
	}
}
