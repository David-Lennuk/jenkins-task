pipeline {
	agent any
	stages {
		stage('Install dependencies') {
			steps {
				sh "npm install"
				}
			}
	stage('test') {
		steps {
			sh "node film.js"
			}
		}
}
}
