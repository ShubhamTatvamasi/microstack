# microstack

https://ubuntu.com/openstack/tutorials

https://microstack.run/docs/single-node

Install microstack:
```bash
sudo snap install microstack --beta
```

Initalize microstack:
```bash
sudo microstack init --auto --control
```

https://10.20.20.1

ID: `admin`, Pass:
```bash
sudo snap get microstack config.credentials.keystone-password
```

create vm:
```bash
microstack launch focal --name test-vm
```
