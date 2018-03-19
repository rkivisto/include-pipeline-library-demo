# requires you to define the library as a global shared library https://jenkins.io/doc/book/pipeline/shared-libraries/#global-shared-libraries
@Library('pipeline-library-demo') _

pipeline {
	agent none
	stages {
		stage('get build cause') {
			agent any
			steps {
				def cause=getBuildCause
				echo cause.getBuildCause()
			}
		}
	}
}
