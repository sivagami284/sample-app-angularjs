node
{
stages{
stage ('checkout ')
{
  
}
stage (' sonarqube scanner ')
	{
		dir("${WORKSPACE}")
		{		
			
		sh 'npm install'
		//sh 'npm audit fix'
		sh 'npm install tslint-sonarts --save-dev'
		sh 'npm install sonar-scanner --save-dev'
		sh 'npm run sonar-scanner'
		}
	}
  }
  }
