node('Built-In') 
{
    stage('Continuous Download_Loan') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_Loan') 
	{
    sh label: '', script: 'mvn package'
	}
}
