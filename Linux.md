# SUMMER SCHOOL - Setup party (Linux Version)

## Required packaged

### 1. Terminal 

Built-in is just fine.

### 2. GIT

Depends on distro: 

__Ubuntu/Debian based:__

```
sudo apt install -y git
```

__Fedora:__

```
sudo dnf install -y git
```

__Centos/Red Hat:__

```
sudo yum install -y git
```

### 3. Docker + Kubernetes

Install docker:
```
curl -fsSL https://get.docker.com -o get-docker.sh && sh get-docker.sh
```

Install docker-compose:
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

Install snap (should be already installed on ubuntu):\
[https://docs.snapcraft.io/installing-snapd/6735](https://docs.snapcraft.io/installing-snapd/6735)

Install MicroK8s using snap:
```
sudo snap install microk8s --classic
```

### 4. VSCode

[https://code.visualstudio.com/](https://code.visualstudio.com/)

### 5. Python

__Ubuntu/Debian based:__
```
sudo apt install -y python3-dev
```

__Fedora:__
```
sudo dnf install -y python-devel
```

__Centos/Red Hat:__
```
sudo yum install -y python python-devel
```

### 6. Java

__Ubuntu/Debian based:__
```
sudo apt install -y openjdk-8-jdk
```

__Fedora:__
```
dnf install java-1.8.0-openjdk
```

__Centos/Red Hat:__
```
sudo yum install java-1.8.0-openjdk-devel
```

### 7. NextFlow

[https://www.nextflow.io/docs/latest/getstarted.html](https://www.nextflow.io/docs/latest/getstarted.html)

### 8. SQLLite3

__Ubuntu/Debian based:__
```
sudo apt install -y sqlite3
```

__Fedora:__
```
sudo dnf install sqlite
```

__Centos/Red Hat:__
```
sudo yum install -y libsqlite3x-devel.x86_64
```

### 9. R

__Ubuntu/Debian based:__

[https://www.digitalocean.com/community/tutorials/how-to-install-r-on-ubuntu-18-04](https://www.digitalocean.com/community/tutorials/how-to-install-r-on-ubuntu-18-04)

__Fedora:__
```
sudo dnf install -y R
```

__Centos/Red Hat:__
```
sudo yum install -y R
```

### 10. RStudio

[https://www.rstudio.com/products/rstudio/download/#download](https://www.rstudio.com/products/rstudio/download/#download)

### 11. Google Account

Create an account on Google:
[https://support.google.com/accounts/answer/27441?hl=en](https://support.google.com/accounts/answer/27441?hl=en)
