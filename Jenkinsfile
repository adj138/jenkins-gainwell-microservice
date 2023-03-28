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
}
