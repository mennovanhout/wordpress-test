# Installation guide

1. run `composer install`
2. Make sure you have deployer installed on you're machine
```bash
$ curl -LO https://deployer.org/deployer.phar
$ mv deployer.phar /usr/local/bin/dep
$ chmod +x /usr/local/bin/dep
```

## Macos

Macos comes with his own version of sed this is a problem that can be solved with:
```bash
$ brew install gnu-sed 
$ brew info gnu-sed
```

The second command shouls show some information and show a PATH..... part.\
Copy that part and paste in the console prepending export example:
```bash
$  export PATH="/usr/local/opt/gnu-sed/libexec/gnubin:$PATH"
```







# Dandelion

1. install cmake and pkg-config ``brew install pkg-config cmake``
2. install dandelion ``sudo gem install dandelion``
3. 