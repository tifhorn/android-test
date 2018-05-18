pipeline {
	agent none
	stages {
		stage('Stage1') {
			steps {
				script {
					println "Test"
				}
			}
		}
	}
}