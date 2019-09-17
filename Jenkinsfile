stage('Build') {
   steps {
       echo 'Building...'
   }
   post {
       always {
           jiraSendBuildInfo branch: 'MS-62-jenkins-branch', site: 'cfraga.atlassian.net'
       }
   }
}
