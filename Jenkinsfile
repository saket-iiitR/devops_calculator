node('master') 
{
    stage('Continuous Download_branch') 
	{
    git 'https://github.com/saket-iiitR/devops_calculator.git'
	}
    stage('Continuous Build_branch') 
	{
    sh label: '', script: 'mvn package'
	}
}