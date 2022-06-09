pipeline{
    agent {
	docker {
		 image 'ubuntu:latest'
		  args '-u root'
                   }
         }
    stages {
       stage('nat') {
          when {
		 branch  'nat'
	      }
	 steps {
	    sh ''' 
		echo 'hello-world'
             '''
	}
     }
	stage('test'){
	   when {
		 branch 'test'
		}
	     steps {
	      sh '''
		 echo 'this is testing stage please make success'
		'''
	}
     }
  }
}
