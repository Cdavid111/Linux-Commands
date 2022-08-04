# Dependencies Error

if have any error of Dependencies we can give a solution write the next commands

Check what Dependencies erros there is 

```
sudo apt-get check
```

then, we must fix the depencies that we don't have , installing them

```
sudo apt --fix-broken Install
```

now we can install this package without any problem

```
sudo dpkg -i "package.deb"
```



