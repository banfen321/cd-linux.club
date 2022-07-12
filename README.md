# cd-linux.club
Greetings, this repository stores all the data for deploying the https://cd-linux.club/ project.

The project allows you to very quickly restore cd-linux.club and all its services. 


1. Deploying a server on GCP using terraform/main.tf

2. Installing Docker packages and containers (gitea+jenkins, grafana+prometheus, nginx-proxy-manager) with configurations and settings using ansible/playbook.yml
 
3. Service deployment requires archives proxy_manager.tar.gz, grafana-docker-stack.tar.gz, gitea, jenkins, mariadb.tar.gz
