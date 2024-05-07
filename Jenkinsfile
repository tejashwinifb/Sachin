pipeline {
    agent any 
stages {
    stage ('clone'){
        steps {
           git branch: 'main', credentialsId: 'git', url: 'https://github.com/tejashwinifb/Sachin.git'
 
}
}
     stage ('trigger') {
            steps {
                script {
                    sh 'touch f1'
             }
        }   
     }
}
