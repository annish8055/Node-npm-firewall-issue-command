# Node-npm-firewall-issue-command
Node npm firewall issue command

# Node npm firewall issue command
Remove your proxy settings at home and switch on at Office networks, This may be irritating, But It worked for me:

npm config set proxy http://xxx.xxx.xxx.4:8080   
npm config set https-proxy http://xxx.xxx.xxx.4:8080
and

npm config rm proxy   
npm config rm https-proxy
