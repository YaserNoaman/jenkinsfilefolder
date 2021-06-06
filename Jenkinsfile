pipeline{

agent any 
    try {
        stages{
            stage("Parallel 1") {
                steps {
                    script {
					    sh 'echo Hello'
                      
                }
            }
		}	
            stage("Feature") {
                steps {
                    steps {
                       script {
					         sh 'echo Hi'
		              }					 
                }
            }
		}	
    }   

  } 
    catch(e) {
        throw e
  }   
}
