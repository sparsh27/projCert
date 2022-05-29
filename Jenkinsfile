node('slave-01'){
        stage('Installing Puppet Agent') {
              
                sh 'yum install puppet-agent'
            }
       
        stage('Configure Puppet agent'){
          
          sh 'source /etc/profile.d/puppet-agent.sh'
          sh 'export PATH=/opt/puppetlabs/bin:$PATH' 
        }
     }

