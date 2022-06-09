pipeline{
    agent any 
   stages {
       stage('nat') {
	 steps {
	    sh ''' 
		echo 'hello-world'
             '''
	}
     }
	stage('test'){
	     steps {
	      sh '''
		 echo 'this is testing stage please make success'
		'''
	}
     }
  }
}
