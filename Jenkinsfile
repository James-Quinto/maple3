pipeline {
	agent any
	
	stages {
		stage("Platform Checkout") {
			steps {
				sh 'uname -a'
			}
		}
		
		stage("Agent Deployment Test") {
			parallel {
				stage("Red Hat") {
					steps {
						sh 'uname -a'
					}
				}
				stage("Ubuntu") {
					steps {
						sh 'uname -a'
					}
				}
				stage("Windows") {
					steps {
						sh 'uname -a'
					}
				}
			}
		}
		
		stage("Performance Test") {
			parallel {
				stage("Red Hat") {
					steps {
						sh 'uname -a'
					}
				}
				stage("Ubuntu") {
					steps {
						sh 'uname -a'
					}
				}
				stage("Windows") {
					steps {
						sh 'uname -a'
					}
				}
			}
		}
		
		stage("Ratt-Tool Test") {
			parallel {
				stage("Red Hat") {
					steps {
						sh 'uname -a'
					}
				}
				stage("Ubuntu") {
					steps {
						sh 'uname -a'
					}
				}
				stage("Windows") {
					steps {
						sh 'uname -a'
					}
				}
			}
		}
		
		stage("Notifying Slack") {
			steps {
				echo "Deploy!"
			}
		}
	}
}
