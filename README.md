## Local PyPi server, powered by Ansible
This role provides a means to provision a local PyPi server, for example in environments where you have no
connection to the Internet.

It comes with a version of the pypiserver package included so you don't need Internet to get it up and running.

# Configure pip for it
After running this role and deploying Pypiserver, you can start using it with the following pip.ini:
```
[global]
index-url = http://pip.example.com:8000/simple
index = http://pip.example.com:8000
```
