# hmodel


# install python


sudo apt update
sudo apt upgrade
```


sudo apt install software-properties-common
```

sudo add-apt-repository ppa:deadsnakes/ppa
```

sudo apt update
```

sudo apt install python3.10
```


python3.10 --version
```

# install vscode
```shell
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg

```

```shell
echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" | sudo tee /etc/apt/sources.list.d/vscode.list
```

```shell
sudo apt update
```

```shell
sudo apt install code
```