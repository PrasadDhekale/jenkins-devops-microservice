pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
				
				echo "Build"
				echo "Path - $PATH"
				echo "BUILD_NUMBER - $env.BUILD_NUMBER"
				echo "BUILD_TAG - $env.BUILD_TAG"
				echo "JOB_NAME - $env.JOB_NAME"
				echo "BUILD_URL - $env.BUILD_URL"
			}
			
		}
		stage('Test'){
			steps{
				echo "Test"
			}
			
		}
		stage('Integration-Test'){
			steps{
				echo "Integration-Test"
			}
			
		}
	}
}
