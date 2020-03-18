pipeline {
   agent any

   stages {
      stage('Hello') {
          
         steps {
            bat 'snowsql -c myconnection --config C:\\Users\\91827\\.snowsql\\config -q "show databases"'
         }
         
      }
      stage('Print'){
          steps{
              bat 'snowsql -c myconnection --config C:\\Users\\91827\\.snowsql\\config -q "use edm_confirmed_dev"'
             
          }
          
      }
   }
}
