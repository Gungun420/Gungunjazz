pipeline 
{
 agent { label "AGNET_TEST" 
       }
			stages 
			{
				stage ('One') 
				{
					steps 
					{
						echo 'Hi,this is poonam from BCM'
					}
				}

				stage ('Two') 
				{
					steps 
					{
						echo 'Hi,this is poonam from BCM1'
					}
				}

				stage ('Three') 
				{
					steps 
					{
						input('Do u wasnt to proceed?')
					}
				}
				stage ('Four') 
				{
					steps 
					{
						echo 'Hi,this is poonam from BCM2'
					}
				}
			}
}
