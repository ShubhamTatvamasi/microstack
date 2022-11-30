# microstack

https://ubuntu.com/openstack/tutorials

Install microstack:
```bash
sudo snap install microstack --beta
```

Initalize microstack:
```bash
sudo microstack init --auto --control
```

ID: `admin`, Pass:
```bash
sudo snap get microstack config.credentials.keystone-password
```

create vm:
```bash
microstack launch focal --name test-vm
```
