# ansible-playbooks
personal Ansible playbooks

## tested environment

### ansible

```
$ ansible --version
ansible 2.4.2.0
  config file = None
  configured module search path = ['/home/kotetsu/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /home/kotetsu/py3-ansible/lib64/python3.6/site-packages/ansible
  executable location = /home/kotetsu/py3-ansible/bin/ansible
  python version = 3.6.4 (default, Dec 19 2017, 14:48:12) [GCC 4.8.5 20150623 (Red Hat 4.8.5-16)]

$ uname -a
Linux cent01 3.10.0-693.11.1.el7.x86_64 #1 SMP Mon Dec 4 23:52:40 UTC 2017 x86_64 x86_64 x86_64 GNU/Linux

$ cat /etc/redhat-release
CentOS Linux release 7.4.1708 (Core)
```

```
$ python3.6 -m venv /home/kotetsu/py3-ansible
$ source /home/kotetsu/py3-ansible/bin/activate

(py3-ansible) [kotetsu@cent01 ~]$ python --version
Python 3.6.3

(py3-ansible) [kotetsu@cent01 ~]$ pip3 --version
pip 9.0.1 from /home/kotetsu/py3-ansible/lib64/python3.6/site-packages (python 3.6)

(py3-ansible) [kotetsu@cent01 ~]$ pip3 install ansible
```

### hosts

```
$ uname -a
Linux cent03 3.10.0-693.11.1.el7.x86_64 #1 SMP Mon Dec 4 23:52:40 UTC 2017 x86_64 x86_64 x86_64 GNU/Linux

$ cat /etc/redhat-release
CentOS Linux release 7.4.1708 (Core)
```
