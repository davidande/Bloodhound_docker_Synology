# Bloodhound_docker_Synology
Install BloodhoundBloodHound Community Edition on Synology NAS

You have to create directories  
volume1/docker/bloodhound  
volume1/docker/bloodhound/app-db  
volume1/docker/bloodhound/bloodhound/bloodhound.config.json (only necessary for custom config)  

  Create a project in Container manager 
  Use the yaml file as project config  
  create  
  Retrieve your inital password in the bloodhound container log  
  Connect to YOUR_NAS_IP:8080  
  use admin and your initial password  
  Change your password  
  
  Enjoy :-)  
  

  based on: https://github.com/SpecterOps/BloodHound/blob/main/examples/docker-compose/docker-compose.yml
  


