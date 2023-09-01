# totp
#

### Google Authenticator command example
```
google-authenticator --secret=/home/$USER/.ssh/totp --time-based --disallow-reuse --rate-limit=3 --rate-time=30 --window-size=3 --step-size=30     --qr-mode=UTF8 --force
```
