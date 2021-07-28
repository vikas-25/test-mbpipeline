pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'yum npm install -y' 
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
