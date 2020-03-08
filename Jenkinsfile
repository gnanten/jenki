pipeline
{
  agent any
  environment
  {
    Hello='ezxtra'
  }
  stages{
    stage('envchdk'){
      environment
  {
    globag='overridden on stg1'
  }
      steps{
        print "${Hello}"
        print "${globag}"
        }
       }
    stage('2ndlevel')
    {
      steps{
        print "${globag}" 
        print "${Hello}"
      }
    }
      }
}
