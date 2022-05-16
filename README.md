# Virtual Box

```bash
  sudo apt update
  sudo apt install virtualbox virtualbox-ext-pack
```

```bash
  wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
  wget -q https://www.virtualbox.org/download/oracle_vbox.asc -O- | sudo apt-key add -
```

```bash
  echo "deb [arch=amd64] http://download.virtualbox.org/virtualbox/debian $(lsb_release -cs) contrib" | \
  sudo tee -a /etc/apt/sources.list.d/virtualbox.list
```

```bash
  sudo apt update
  sudo apt install virtualbox
```

# Link for BIOS
[BIOS](https://www.asus.com/support/FAQ/1043786/)
