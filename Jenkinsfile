pipeline {

   agent any 
     
       tools {
          
          maven 'Maven3.5.0'
          jdk 'OpenJDK1.8' 
       } 
   
     stages {
         
        stage('Build') {
        
            steps {
            
                 sh '''
                     echo "This is start up of declarative pipeline multibranch"
                     echo "${JAVA_HOME}"
                     echo "${M2_HOME}"
                 '''
                 
            }
            
         }
      }
}
