# Tareq - BDL

Hello everyone, here are some notes from me as an example, feel free to create your own folder and readme file :)


### - Installing node using NVM:

this can be done using the following commands:

(we are using version 18.15.0 in this example but the same can apply to any other version)
```text
1. sudo apt install curl
2. curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
3. nvm install 18.15.0
```

### - updating node:

using these commands:

```text
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
```

### - switching to another node versions using NVM:

```text
nvm use 18.15.0
```