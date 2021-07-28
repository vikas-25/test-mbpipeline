pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           echo "testing application..."
        }
      }

         stage("Deploy application") { 
         steps { 
           echo "deploying application..."
         }

     }
  
   	}

   }
