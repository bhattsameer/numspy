# Numspy 1.0 [![Python 3.x](https://img.shields.io/badge/Made%20with-Python3.x-1f425f.svg)](http://www.python.org/download/)

<img src="logo.png" alt="NumSpy logo" width="150px" height="150px"/>

A python module for sending free sms as well as finding details of mobile number via website 
<a href="http://www.way2sms.com">Way2sms</a>


# Installation
```
pip3 install numspy
```
<a href="https://pypi.org/project/numspy/
">https://pypi.org/project/numspy/</a>

# Requirements
```
Way2sms account
```

# Modules used 
```
BeautifulSoup4
huepy
requests
urllib.request
```

# Usage

<b>Send SMS</b>

```
    from Numspy import Way2sms

    w2s = Way2sms()

    w2s.login(USERNAME, PASSWORD)

    w2s.send(MOBILE_NO, MSG)

    w2s.logout()
```

<b> Schedule SMS </b>

```
    from numspy import Way2sms

    w2s = Way2sms()

    w2s.login(USERNAME, PASSWORD)

    w2s.schedule(MOBILE_NO, MSG, DATE, TIME)
    # DATE should be in format DD/MM/YYYY and TIME in 24h HH:mm

    w2s.logout()
```

<b> Find Details of any Mobile Number </b>

```
    from numspy import Way2sms

    w2s = Way2sms()

    w2s.login(USERNAME, PASSWORD)

    w2s.details(MOBILE_NO)

    w2s.logout()Contributing
```
</br>
Feel free to make a pull request! :)</br>
for more details visit check: 
<a href="https://pypi.org/project/numspy/
">https://pypi.org/project/numspy/</a>
