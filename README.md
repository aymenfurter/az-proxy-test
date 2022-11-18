# AZ Proxy Test

# Code
```bash
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
az login
docker run --name=hitch -p 443:443 hitch
HTTP_PROXY=http://127.0.0.1:443
HTTPS_PROXY=http://127.0.0.1:443
az account list
NO_PROXY=*
no_proxy=*
az account list
```
