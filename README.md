# Wtf is this?
This small tool monitors World of Warcraft updates. It allows you to notify yourself whenever World of Warcraft has pushed an updated. (Discord Webhook supported).

# How to use
Install the Dotnet framework.
Clone the application.
Start application in a screen instance.

# instructions
```
git clone https://github.com/ferib/WowUpdateChecker.git
cd WowUpdateChecker
screen dotnet run
```

# Dotnet
More info for the Dotnet framework
https://dotnet.microsoft.com/download/linux-package-manager/ubuntu16-04/runtime-current

# ubuntu 16.04 manual
installing dotnet framework
```
wget -q https://packages.microsoft.com/config/ubuntu/16.04/packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
sudo apt-get install apt-transport-https
sudo apt-get update
wget http://security.ubuntu.com/ubuntu/pool/main/i/icu/libicu55_55.1-7ubuntu0.4_amd64.deb
sudo dpkg -i ./libicu55_55.1-7ubuntu0.4_amd64.deb
sudo apt-get install dotnet-sdk-2.2
```

installing Screen
```
sudo apt-get install screen
```

download and run application
```
git clone https://github.com/ferib/WowUpdateChecker.git
cd WowUpdateChecker
screen dotnet run
```
