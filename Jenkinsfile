pipeline {
		agent {label 'Windows_Agent'}
 		stages{
		  stage {
        steps{
          git branch: 'main', url:'https://github.com/sprasad321/b7-java.git'
        }
      }
      stage(clean){
				steps{
					bat 'mvn clean'
					}
			}
stage(install){
				steps{
					bat 'mvn clean install'
					}
			}
		}
}
