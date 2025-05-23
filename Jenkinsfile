pipeline {
  agent any
  tools { 
        maven 'Maven_6_1_130'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify org.sonarsource.scanner.maven:sonar-maven-plugin:3.11.0.3922:sonar -Dsonar.projectKey=geo123fdgufdsgk -Dsonar.organization=georgesteward -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=2541c79874304bbbb38fa3d633dce25a346e33c3'
			}
        } 
  }
}
