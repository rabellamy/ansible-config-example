## Components

* [Ansible](https://www.ansible.com/) (>=2.2.1)
* [Vagrant](https://www.vagrantup.com/) (>=1.9.1)
* [Virtual Box](https://www.virtualbox.org/) (>=5.1.12r112440)


**_Please note that this stack has only been tested with the above versions._**

### Steps

#### 1. Install Ansible
* On a Mac
```bash
$ brew install ansible
```
* [other methods](http://docs.ansible.com/ansible/intro_installation.html#getting-ansible)

#### 2. Install Vagrant with plugins
```bash
$ brew cask install vagrant
```

#### 3. Install Virtual Box (>=5.1.12r112440)
```bash
$ brew cask install virtualbox
```
#### Clone repo
```bash
$ git clone git@github.com:rabellamy/ansible-config-example.git
$ cd ansible-config-example
```

#### Start VM
```bash
$ vagrant up
```

#### SSH into VM
```bash
$ vagrant ssh
```
