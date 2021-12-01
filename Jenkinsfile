pipeline
{
  agentany
  stages
  {stage (' exactly command')
   {
     steps
     {
       sh 'touch abc.txt'
       sh 'echo abc.txt'
       sh 'echo $_MAVEN-HOME'
     }
   }
  }
}
