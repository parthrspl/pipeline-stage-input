pipeline{			
    agent any

    stages{
        stage('Build'){	
			input{
                    message "Please specify environment:"			
                    ok "OK"
					submitter "dummy"		
                	}			
            			
            steps{			
				echo "We are building for ${environment}, ${version}, and we are deploying to environment: ${to_deploy_to_environment}"
				echo "region:${region}, myText: ${myText}, myPassword: ${myPassword}, and myFile: ${myFile}"
				echo "submitter is: ${whoIsSubmitter}"
				echo "selected credentials is: ${myCredentials}"
			}
        }			
    }			
}
