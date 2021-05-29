pipeline { 
  
   agent any

   stages {
   
     stage('maven') { 
        steps { 
           sh 'clean install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
