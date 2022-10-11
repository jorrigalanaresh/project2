pipeline{
	agent any
		tool('maven'){
			maven "mvn363"
			}
		stages{
			stage{
				steps{ 
					script{  
						sh 'mvn clean test package'
						}
					}
				}
			}
}
