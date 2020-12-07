# Ansible Demo

## Talking Points

* What are some of the considerations of ops vs dev?
* Why is manually going into servers and updating them not a good idea?
* Why is a bash script not sufficient for managing many servers?
* What do we mean by infrastructure as code?
* What are some solutions (Chef, Puppet, Ansible, etc)?
* What are the pros/cons of Ansible?
* Why have have we combined dev and ops into DevOps (and even DevSecOps)?

## Useful Commands

```
ansible --version
ansible all --list-hosts
ansible-playbook playbook.yml
```

```
ansible-galaxy install -r requirements.yml
```

```
ansible-vault encrypt vars.yml
ansible-vault view vars.yml
ansible-vault edit vars.yml

ansible-playbook playbook.yml --ask-vault-pass
```
