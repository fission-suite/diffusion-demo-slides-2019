# Live From Laptop ⚡️

{tag line}

---

## Install IPFS

```shell
# MacOS
brew cask install ipfs

# Linux
snap install ipfs-desktop

# Windows
choco install ipfs-desktop
```
---

## Download Fission

**Mac:** https://github.com/fission-suite/web-api/releases/download/1.9.0/macos-cli

**Linux:** https://github.com/fission-suite/web-api/releases/download/1.9.0/deb-cli

---

## Install Fission
```bash
# Or wherever you may have downloaded it to
cd ~/Downloads

# Give it executable permission
sudo chmod +x ./macos-cli

# And move the file to your PATH:
sudo mv ./macos-cli /usr/local/bin/fission
```

---

## Register
```bash
# Get your free account setup
fission register
```

---

## It's ALIVE!

```bash
# Create a simple site
mkdir my-sweet-fission-app
cd my-sweet-fission-app
echo "Hello Diffusion\!" >> index.html

curl https://media1.tenor.com/images/27e8b015e35130e7b4f62dc3d9a95dbe/tenor.gif --output john.gif
echo "<br/><img src=\"john.gif\"/>" >> index.html

# Let it loose
fission up
open https://ipfs.runfission.com/ipfs/Qmerj2V9i7Qq4JKoM1pKtv1wDaRgcp3E6mMPcZEEBx5Uij/

```

---

## Serving directories

---

## Serving individual files

---

## Serving Web apps

---

## Watching

---

# Thank you
(Btw, these slide are all on run from fission live 😉)
