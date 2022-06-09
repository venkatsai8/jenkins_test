pipeline{
   agent { docker {
		image 'ubuntu:latest' 
                  args '-u root'
     }
    }
   stages {
       stage('nat') {
	 steps {
	    sh ''' 
		echo 'hello-world'
             '''
	}
     }
  }
}
