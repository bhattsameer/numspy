# Numspy

A python module for sending free sms as well as finding details of mobile number via website 
<a href="http://www.way2sms.com">Way2sms</a>

<img src="https://img.shields.io/badge/Made%20with-Python3.x-1f425f.svg"/>

# Installation
```
pip3 install numspy
```
# Usage

# Send SMS

```
    from Numspy import Way2sms

    w2s = Way2sms()

    w2s.login(USERNAME, PASSWORD)

    w2s.send(MOBILE_NO, MSG)

    w2s.logout()
```

# Schedule SMS

```
    from numspy import Way2sms

    w2s = Way2sms()

    w2s.login(USERNAME, PASSWORD)

    w2s.schedule(MOBILE_NO, MSG, DATE, TIME)
    # DATE should be in format DD/MM/YYYY and TIME in 24h HH:mm

    w2s.logout()
```
# Find Details of a Mobile number

```
    from numspy import Way2sms

    w2s = Way2sms()

    w2s.login(USERNAME, PASSWORD)

    w2s.details(MOBILE_NO)

    w2s.logout()Contributing
```

Feel free to make a pull request! :)
