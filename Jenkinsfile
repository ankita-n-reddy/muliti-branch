pipeline { 
			agent{
			label{
			label"built-in"
			customWorkspace"/mnt/jenkins-master
			}
			}
			stages{
			stage("one"){
			steps{
			echo "this is master branch"
			}
			}
			steps{
			echo "this is dev branch"
			}
			}			
  }
