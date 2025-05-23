pipeline {
  agent any
  tools { 
        maven 'Maven_3_5_2'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=geo123fdgufdsgk -Dsonar.organization=georgesteward -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=2541c79874304bbbb38fa3d633dce25a346e33c3'
			}
        } 
  }
}
