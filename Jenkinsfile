pipeline {
	agent any
		stages {
		stage('One') {
			steps {
				echo 'I am executing stage 1'
			}
		}
		stage('Two') {
			steps {
				input('In pipeline, We take decision. Can we proceed?')
			}
		}
		stage('Three') {
			steps {
				echo "Running Last Three"
			}
		}
		
	}
}
