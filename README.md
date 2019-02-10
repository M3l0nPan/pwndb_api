
# PWNDB API

### Resume : 

Script to query the pwndb database

### Requirements :

```
Python >= 3.3
argparse
request
```

Dependencies can be installed via PIP or a package manager

To install all dependencies with PIP :


```
pip3 install -r requirements.txt --upgrade --user
```

Your Tor proxy should be turn on when running the script, the default address is http://127.0.0.1:9050 or you must specify your Tor proxy  address with the --proxy option.

### Usage :

Search an email :

```
pwndb --email EMAIL
```

Search just email local part :

```
pwndb --localpart EMAIL_LOCALPART
```

Search just email domain :

```
pwndb --localpart EMAIL_DOMAIN
```

Search a password :

```
pwndb --password PASSWORD
```

### Disclaimer :

Usage of this for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. Only use for educational purposes.


### Licence :

This project is licensed under the terms of the GLPv3
