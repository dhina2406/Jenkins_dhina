pipeline{
 any angent
     stages{
         stage('build'){
            steps{
                 sh 'hostname; whoami'
            }
         }
     }
}
