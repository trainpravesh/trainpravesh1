pipeline {
	agent any 
	
	        stages { 
	
		              stage("build") { 
			
			                            steps { 
                                           echo 'This is the first test on build through jenkinsfile.'
                                        }
                                  }      
                  stage("test") { 
		                              	steps { 
                                              echo 'This is the first test on test stage through jenkinsfile.'
                                          }
		                            }
	                }
         }
