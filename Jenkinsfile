node('master')

{

stage('ContinuousDownload_loan') 
   
	 {
	
    git 'https://github.com/Bikash-Debnath/maven.git'
    
	}

stage('Continuousbuild_loan') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}
}

