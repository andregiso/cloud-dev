#Description

☁️Simple python app implemented to cloud environment☁️

## Deployment

- [Python](https://www.python.org/downloads/)🐍
- [Docker](https://www.docker.com/) 🐋
- [Linux]https://ubuntu.com/download🐧
- [Azure]https://docs.microsoft.com/pl-pl/cli/azure/install-azure-cli-macos🗽

## Development

🖥️ Virtual Machine:
az loign --use-device-code
az group create -n cloud-dev -l westeurope
az vm create --resource-group cloud-dev --name virtualmachine --size "Standard_B1ls" --image "Canonical:0001-com-ubuntu-server-focal:20_04-lts-gen2:latest" --public-ip-sku Standard --admin-username ubuntu

💾 Docker and nginx installation:
sudo apt-get install docker.io
sudo docker pull nginx
docker build -t html-server-image:v1 .
docker tag html-server-image:v1 nimranos/html-server-image
sudo docker run -d -p 5000:5000 nimranos/html-server-image:latest nginx

📱AppService
Cloning repository:
![image](https://imgur.com/a/ztLYKQ2)

Deploy:
![image](https://imgur.com/a/5AyMsLc)
