pipeline
	{
	agent any
	stages
		{
		stage("GIT")
			{
			steps
				{
					git "https://github.com/gopal-jogi/Jenkins_practice.git"
				}
			}
		stage("Run")
			{
			steps
				{
					java Demo.java
						}
				}
			}
		}
	}
