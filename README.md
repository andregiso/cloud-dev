#Description

☁️Simple python app implemented to cloud environment☁️

## Deployment

- [Python](https://www.python.org/downloads/)🐍
- [Docker](https://www.docker.com/) 🐋
- [Linux](https://ubuntu.com/download)🐧
- [Azure](https://docs.microsoft.com/pl-pl/cli/azure/install-azure-cli-macos)🗽

## Development

🖥️ Virtual Machine:
```bash
az loign --use-device-code
```
```bash
az group create -n cloud-dev -l westeurope
```
```bash
az vm create --resource-group cloud-dev --name virtualmachine --size "Standard_B1ls" --image "Canonical:0001-com-ubuntu-server-focal:20_04-lts-gen2:latest" --public-ip-sku Standard --admin-username ubuntu
```

💾 Docker and nginx installation:
```bash
sudo apt-get install docker.io
```
```bash
sudo docker pull nginx
```


📱AppService

- Cloning repository:

![](https://github.com/andregiso/cloud-dev/blob/main/images/src3.png)


- Deploy:

![](https://github.com/andregiso/cloud-dev/blob/main/images/src4.png)
