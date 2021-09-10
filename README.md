# Simple-pipeline-Jenkins

Stes to create a simple two stage pipeline-

```

1. Add the build pipeline pipeline from Manage plugins.

2. Create a new item as a pipeline project and add the following pipeline script.
pipeline {	 
	agent any	 
		stages {     	 
    		stage('First Stage') {
        			steps {               	 
            			echo 'Hello World'          
        			}     	 
    		}     	 
    		stage('Second Stage') {          	 
        			steps {               	 
            			echo 'Hello Again'               	 
            			echo 'A third time Hello'          	
        			}     
    		}	
	}
}

3. Build the project and view the logs.

```
