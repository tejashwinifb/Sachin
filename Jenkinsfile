Pipeline {
      agent any
      stages {
         stage('clone'){
           steps {
             git branch: 'main', credentialsId: 'git,url:'https://github.com/tejashwinifb/Sachin.git'
           }
                     }
         stage('build'){
            steps {
              sh "ls"
            }
         }
         stage('trigger'){             
           steps {
            sh "touch file1"
           }
    }
 }
}
