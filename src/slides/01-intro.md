# Fission Live
## ⚡️
#### There Is No Step Two...

---

![](https://imgur.com/1AsURoo.png)

_🔖 Slides at https://slides.runfission.com_

---

## Install IPFS
_A one line prerequisite_

```shell
# MacOS
brew cask install ipfs

# Linux
snap install ipfs-desktop

# Windows
choco install ipfs-desktop
```

_Other installation options can be found at https://guide.fission.codes/installation_

---

## Install Fission (MacOS)
```bash

brew tap fission-suite/fission
brew install fission-cli
```

---

## Install Fission (Linux)

```bash
# Download our binary
curl
  \ https://github.com/fission-suite/web-api/releases/download/1.16.0/deb-cli
  \ -o fission-cli

# Give it executable permission
sudo chmod +x ./fission-cli

# And move the file to your PATH:
sudo mv ./fission-cli /usr/local/bin/fission
```
️_Yum and Aptitude are on their way! We promise!_ 💜

---
## Going Live ⚡️

![](https://imgur.com/rT0JFjL.gif)

---

## Serving Directories

```bash
rm index.html
fission up
```

![](https://i.imgur.com/fWhCDMf.png)

---

## Serving individual files

```bash
# serve from an existing directory
open https://diffdemo.runfission.com/john.gif

# serve just one file
fission up john.gif
```

---

## Serving Web Apps

```bash
# Install Gatsby
npm i -g gatsby-cli

# Get a template of your choosing
gatsby new fission-demo
  \ https://github.com/greglobinski/gatsby-starter-hero-blog

# Navigate to the project directory
cd fission-demo

# Build and deploy the site to ipfs
gatsby build
fission up public
```
https://blog.runfission.com

---

## Portable User Settings
![](https://imgur.com/QlK6NCf.png)

https://fission-suite.github.io/ipfs-user-settings/

---

# Thanks for watching!
(Btw, these slide are all on run from fission live 😉)
