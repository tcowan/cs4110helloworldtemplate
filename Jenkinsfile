pipeline {
	agent any

	stages {
		stage('Build') {
			steps {
				echo 'Building..'
				sh 'javac -o HelloWorld *.java'
			}
		}
		stage('Test') {
			steps {
				echo 'Testing..'
				sh 'cucumber -s'
			}
		}
		stage('Grade') {
			steps {
				echo 'Grading....'
			}
		}
	}
}
