node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/umeshkiran92/multi.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
  
}
