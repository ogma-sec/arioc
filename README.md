# arioc
All ressources in one command

# Usage
First, create a local copy of ressources tree:
```
arioc -r
```

Then, make a word based research:
```
arioc -s xss
```

Get article links containing the searched word from:
- Hacktrickz
- Hacktrickz Cloud
- PayloadAllTheThing
- PortSwigger Labs and materials
- ANSSI guides
- OWASP WSTG
- Ired Teams

# Faster use
- Create a symbolic link to in-PATH directory
```
sudo ln -s <arioc/path>/arioc /usr/bin/arioc
```

- Create an `ar` alias in ̀`~/.bashrc` for arioc fast use :
```
alias ar="/usr/bin/arioc"
```
