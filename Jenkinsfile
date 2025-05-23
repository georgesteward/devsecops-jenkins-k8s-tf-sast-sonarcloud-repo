pipeline {
  agent any
  tools { 
        maven 'Maven_6_1_130'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify'
			}
        } 
  }
}
