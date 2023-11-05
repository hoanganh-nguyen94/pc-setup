# pc-setup

```shell
# install chocolate
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

choco install argocd-cli flutter maven golang gradle istioctl jdk8 k3d k9s kind kubernetes-cli kubernetes-helm Minikube nodejs terraform flux googlechrome vlc openvpn-connect intellijidea-ultimate 7zip git -y


choco install composer --version 6.3.0 -y
choco install kustomize --version 4.4.1 -y
choco install python --version 3.10.2 -y
choco install jdk8 --version 8.0.211 -y
choco install maven --version 3.8.5 -y
choco install argocd-cli --version 2.3.1 -y
choco install docker-desktop --version 4.6.0 -y
choco install kubernetes-cli --version 1.23.4 -y
choco install kubernetes-helm --version 3.8.0 -y
choco install make --version 4.3 -y
choco install minikube --version 1.25.2 -y
choco install sbt --version 1.6.2 -y
choco install android-sdk --version 26.1.1 -y
choco install nodejs-lts --version 16.14.0 -y
choco install yarn --version 1.22.15 -y
choco install terraform --version 1.1.7 -y
choco install awscli --version 2.4.25 -y
choco install k9s --version 0.25.18 -y
choco install 7zip --version 21.7 -y
choco install git --version 2.35.1.2 -y
choco install googlechrome --version 99.0.4844.74 -y
choco install vlc --version 3.0.16 -y
choco install openvpn-connect --version 3.3.4 -y
choco install flux --version 0.27.3 -y

```

#Mac os
```shell
brew install --cask google-chrome && \
brew install git && \
brew install --cask webstorm && \
brew install node@20 && \
brew install docker && \
brew install --cask microsoft-office && \
brew install --cask tradingview

```
