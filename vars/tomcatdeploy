def call(ip,warname,Credentials){
sshagent(["${Credentials}"]) {
                    
            sh "scp -o StrictHostKeyChecking=no target/${warname}*.war  ec2-user@${ip}:/opt/tomcat-9/webapps"
            }
}
