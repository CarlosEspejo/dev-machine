# dev-machine
Ansible playbook for base configuration of my dev-machine

### Requirements

```shell
$ xcode-select --install
$ sudo easy_install pip
$ sudo pip install ansible
```

### To Run
`ansible-playbook -i inventory dev-machine.yml -K`
