// requires you to define the library as a global shared library https://jenkins.io/doc/book/pipeline/shared-libraries/#global-shared-libraries
@Library('pipeline-library-demo@master') _

pipeline {
	agent none
	stages {
		stage('get build cause') {
			agent any
			steps {
				// getBuildCause() is from pipeline-library-demo
				echo getBuildCause()
			}
		}
	}
}
