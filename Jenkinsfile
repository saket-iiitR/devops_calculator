node('master') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/saket-iiitR/devops_calculator.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
}