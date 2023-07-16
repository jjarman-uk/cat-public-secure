## How  to unencrypt the repo

``` console
gpg --decrypt --output catnotcat.tar.gz catnotcat.tar.gz.gpg
Enter the supplied password
tar -xzvf catnotcat.tar.gz
```