# Socks5 Proxy in Terminal
Add this script to ~/.bash_profile or Execute Once (If close terminal,the proxy settings will be clear).
```
export export all_proxy=socks5://127.0.0.1:1080
```

# Socks5 Proxy in Terminal (zsh)

## Open zshrc
```
vim ~/.zshrc  
```

## Insert this to zshrc
```
# proxy list
alias proxy='export all_proxy=socks5://127.0.0.1:1080'
alias unproxy='unset all_proxy'
```

## Use proxy
```
proxy
```

## Use direct (without Proxy)
```
unproxy
```

# Config git to use Socks5 Proxy
```
git config --global http.proxy 'socks5://127.0.0.1:1080'
git config --global https.proxy 'socks5://127.0.0.1:1080'
```

