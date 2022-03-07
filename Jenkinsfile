node('built-in') 
{
    stage('Continuous_Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous_Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
