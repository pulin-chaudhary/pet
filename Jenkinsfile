pipeline 
{

agent any 

   stages {
   
        stage('Cleaning the code')
        {
               steps
               {
                 sh 'mvn clean'
                 }
    }
        stage ('unit testing')
      {
        steps
         {
             sh 'mvn test'
        }
            }
   }
   
}
