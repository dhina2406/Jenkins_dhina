pipeline{
     stages{
         stage('build'){
            steps{
                 sh 'hostname; whoami'
            }
         }
     }
}
