pipeline{
    agent any
    environment{
    FOO="PIPELINE"
   }

 stages{
     stage("local"){
         environment{
             BAR ="STAGE"
            }
         steps{
             echo "FOO $FOO BAR $BAR"
         }
         
         
        }
 }
     
 }
 
