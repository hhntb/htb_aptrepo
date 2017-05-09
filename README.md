# Remote APT Package Repository

APT Package Repository containing custom system dependencies.

For now: **Ubuntu 16.04 (xenial) only!**

---
### EXPERIMENTAL, SYSTEM MAY BE DAMAGED!
---



## Connect a System

Install package ``apt-transport-https``:  
*(apt-get does not support https by default)*

```
sudo apt-get install apt-transport-https
```

Add Repo to APT-Sources (``/etc/apt/sources.list``):

```
deb https://raw.githubusercontent.com/hhntb/htbrepo/master xenial main
```

Update APT-Sources:

```
sudo apt-get update
```

Install needed package:

```
sudo apt-get install needed-package-name
```
