pipeline{
	agent any
		tool(maven){
			maven 'mvn363'
			}
		stages{
			stage{
				steps{ 
					script{  
						'mvn clean test package'
						}
					}
				}
			}