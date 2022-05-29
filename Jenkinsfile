node('slave-01'){
        stage('Installing Puppet Agent') {
              
                sudo bash -c 'yum install puppet-agent'
            }
       
        stage('Configure Puppet agent'){
          
          sh 'source /etc/profile.d/puppet-agent.sh'
          sh 'export PATH=/opt/puppetlabs/bin:$PATH' 
        }
     }

