 
 # Chromely.CrossPlat

### Dotnet 7:
```
wget https://download.visualstudio.microsoft.com/download/pr/253e5af8-41aa-48c6-86f1-39a51b44afdc/5bb2cb9380c5b1a7f0153e0a2775727b/dotnet-sdk-7.0.100-linux-x64.tar.gz
```
```
sudo mkdir /usr/bin/dotnet
```
```
sudo tar xzf dotnet-sdk-7.0.100-linux-x64.tar.gz -C /usr/bin/dotnet
```
```
echo 'export DOTNET_ROOT=/usr/bin/dotnet' >> ~/.bashrc
```
```
echo 'export PATH=$PATH:/usr/bin/dotnet' >> ~/.bashrc
```

### Publish:
```
dotnet publish -c Release -r linux-x64
```
```
dotnet publish -c Release -r linux-arm
```