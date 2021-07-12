# Ansible Technical Challenge _ Submisssion by Chirag Modi

Hi there, thanks for giving me this oppurtunity to complete this Challege. Here is my submission. 

## Requirements:

- Control Node Requirements:
	- Python
	- pip
	- boto and boto3

- On the Dynamic Inventory(inventory/aws_ec2.yml), you will need to place your access keys and secret keys. I tried to encrypt these, but just couldn't get it working. If there is more time, I'd definitely like to try. 
```
aws_access_key: '<<your-access-key-here>>'
aws_secret_key: '<<your-secret-key-here>>'
```

## Usage:

```
ansible-galaxy collection install -r collections/requirements.yml
ansible-playbook -i inventory/aws_ec2.yml site.yml --ask-vault-pass
```
Reach out to me directly for the password. The Access keys and secret key on the vars file have been encrypted for security reasons ;) - Got one part working! 