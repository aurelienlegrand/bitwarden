# bitwarden
bitwarden credentials manager hosting

Use the following to copy your public key to the host instances: 
    ssh-keygen
    ssh-copy-id -i ~/.ssh/id_rsa.pub user@host`


TODO:
* Install Docker, Docker Compose
* Install, deploy, restart Bitwarden
* Create GCP instance using ansible playbook (or Terraform)
* Manage DNS records for the instance
* Get install id/key from https://bitwarden.com/host