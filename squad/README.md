## Squad Dedicated Server

This ansible playbook is used to automaticaly provision and deploy a fully up to date squad dedicated game server to the AWS cloud to whichever region you would like.


Usage:
```
ansible-playbook upsquad.yml

ansible-playbook gosquad.yml
```

The `upsquad` play provisions the ec2 instance while the `gosquad` play configures the provisioned servers.

