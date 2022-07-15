
pipeline
{
   agent any
   stages {
     stage("PrepareBuild") {
      steps{
         stage('Build'){
         echo "Inside the build stage"
        }
      }
       
      stage("Preparetest") {
      stage('Test'){
         echo "Inside the Test stage"
        }
      }     
       stage("PrepareDeploy") {
       stage('Deploy'){
         echo "Inside the Deploy stage"
       }
       }  
       
       }
      
   }
}











   
