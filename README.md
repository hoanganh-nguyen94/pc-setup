# pc-setup

```shell
# install chocolate
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

choco install argocd-cli flutter maven golang gradle istioctl jdk8 k3d k9s kind kubernetes-cli kubernetes-helm Minikube nodejs terraform flux googlechrome vlc openvpn-connect intellijidea-ultimate 7zip git -y



```
