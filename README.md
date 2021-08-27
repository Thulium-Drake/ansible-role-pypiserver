## TITLE


# Configure pip for it
After running this role and deploying Pypiserver, you can start using it with the following pip.ini:
```
[global]
index-url = http://pip.example.com:8000/simple
index = http://pip.example.com:8000
dest: '/etc/pip.conf'
```
