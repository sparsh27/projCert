pipeline {
   node("slave-01") {
      stages {
        stage('Installing Puppet Agent') {
            steps {
                sh 'sudo yum install puppet-agent'
            }
        }
        stage('Configure Puppet agent'){
          steps{
          sh 'source /etc/profile.d/puppet-agent.sh'
          sh 'export PATH=/opt/puppetlabs/bin:$PATH' 
        }
    }
}
   }
}
