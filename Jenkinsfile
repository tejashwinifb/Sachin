Pipeline{
      agent any
      stages
         stage('clone'){
           steps{
             git branch:'main',credentialsid:'git',url:'https://github.com/tejashwinifb/Sachin.git'
           }
                     }
         stage('build')
            steps{
              sh ls
            }
         stage('trigger')              
           steps {
             touch file1
           }
}
