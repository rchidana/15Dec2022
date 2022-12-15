# 15Dec2022

PDF Links for Reference : https://drive.google.com/drive/folders/11YkXrziAG3f-U7XnfyawJ2kAu-5Metjr?usp=sharing

### Installing Latest Docker CE on Ubuntu:

### Update Ubuntu Libraries
```
sudo apt-get update
```


### Install Latest version of Docker CE
```
sudo apt-get install docker.io
```

### Check if docker service is running
```
sudo systemctl status docker
```

### If not running, start it
```
sudo systemctl start docker
```

### Add ubuntu user rps to docker user group
```
sudo usermod -aG docker rps
```

### Open a new Terminal (duplicate Putty session)

### OR refresh docker group with the command (so that the usermod takes effect)

```
newgrp docker
```

### Check if docker is running
```
docker version
```

### Run Docker hello-world image
```
docker run -it hello-world
```


### For installing specific Docker version, check out docker documentation : https://docs.docker.com/engine/install/ubuntu/
