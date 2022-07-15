node('built-in') 
{
    stage('Continuous download_Master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
        }
} 
