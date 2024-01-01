# apt-repo

APT repository hosted on github to distributed my debian based packages.

### Installation

```
wget -O - https://raw.githubusercontent.com/maker-ATOM/apt-repo/master/public.key | sudo apt-key add -

echo "deb https://maker-atom.github.io/apt-repo stable main" | sudo tee /etc/apt/sources.list.d/maker-ATOM.list

sudo apt update
```

### Usage

```
sudo apt install kinet
```

### Remove

```
sudo apt remove kinet
```
