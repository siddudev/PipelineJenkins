pipeline{
	agent any
	stages{
		stage("clone"){
			steps{
				echo "cloning..repo.."
			}
		}
		stage("build"){
			steps{
				echo "Building package"
			}
		}
		stage("execute"){
                steps{
                        echo "Executing package"
                        }
                }
                stage("Main"){
                        steps{
                                echo "Main sent successfully"
                        }
                }
	}
}

