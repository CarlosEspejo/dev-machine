# dev-machine
Ansible playbook for base configuration of my dev-machine

### Requirements

```shell
# command line tools
$ xcode-select --install

# Install Homebrew
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

$ brew install python
$ sudo pip install ansible
```

### To Run
`ansible-playbook -i inventory dev-machine.yml -K`
