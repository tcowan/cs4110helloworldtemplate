// added a comment
// a new comment from local on grandparent
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
            }
        }
        stage('Grade') {
            steps {
                echo 'Grading....'
            }
        }
    }
}
