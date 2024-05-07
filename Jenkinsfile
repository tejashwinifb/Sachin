Pipeline{
      agent any
      stages{
         stage('clone'){
           steps{
             checkout scmGit(branches:[[name:'*/main]],extensions:[],UserRemoteconfigs:[[credentialsId:'git',url:'https://github.com/tejashwinifb/Sachin.git']])
           }
                     }
         stage('build'){
            steps{
              sh "ls"
            }
         }
         stage('trigger') {             
           steps {
            sh "touch file1"
           }
}
 }
}
