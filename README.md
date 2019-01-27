# Bitwarden
bitwarden credentials manager hosting

## Usage

Install requirements:
```
ansible-galaxy install -r requirements.yml
```

Use the following to copy your public key to the host instances: 
```
ssh-keygen
ssh-copy-id -i ~/.ssh/id_rsa.pub user@host
```

Run the base setup playbook: 
```
ansible-playbook -i inventories/prod.yml setup.yml
```

## TODO
* Install Docker, Docker Compose
* Install, deploy, restart Bitwarden
* Create GCP instance using ansible playbook (or Terraform)
* Manage DNS records for the instance
* Get install id/key from https://bitwarden.com/host
