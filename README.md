# Socks 5 in Terminal
Add this script to ~/.bash_profile or Execute Once (If close terminal,the proxy settings will be clear).
```
export http_proxy=socks5://127.0.0.1:1080
export https_proxy=socks5://127.0.0.1:1080
```

# Config git to use Socks 5
```
git config --global http.proxy 'socks5://127.0.0.1:1080'
git config --global https.proxy 'socks5://127.0.0.1:1080'
```
