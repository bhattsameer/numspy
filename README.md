# Numspy 1.0 [![Python 3.x](https://img.shields.io/badge/Made%20with-Python3.x-1f425f.svg)](http://www.python.org/download/) [![PyPI](https://img.shields.io/badge/Made%20with-PyPI-1f425f.svg)](http://www.pypi.org/project/numspy)

<img src="logo.png" alt="NumSpy logo" width="150px" height="150px"/>

A python module for sending free sms as well as finding details of mobile number via website 
<a href="http://www.way2sms.com">Way2sms</a>


# Installation
```command
pip3 install numspy
```

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

```python
from Numspy import Way2sms
w2s = Way2sms()
w2s.login(Way2sms_Username, Way2sms_Password)
w2s.send(Mobile_Number, Message)
w2s.logout()
```

<b> Schedule SMS </b>

```python
from numspy import Way2sms
w2s = Way2sms()
w2s.login(Way2sms_Username, Way2sms_Password)
w2s.schedule(Mobile_Number, Message, Date, Time)
# DATE should be in format DD/MM/YYYY and TIME in 24h HH:mm
w2s.logout()
```

<b> Find Details of any Mobile Number -> Work even without Way2sms account</b>

```python
from numspy import Way2sms
w2s = Way2sms()
w2s.details(Mobile_Number)
```
# Example 

1. Upadate <a href="https://github.com/bhattsameer/numspy/blob/master/Examples/credentials.py">credentials.py</a> file with your way2sms credentials.

2. Run python3 numspy_example.py 

</br>
Feel free to make a pull request! :)
</br>
for more details visit check: https://pypi.org/project/numspy/

# Also Visit

NumSpy-Public API  : [https://github.com/bhattsameer/numspy-api](https://github.com/bhattsameer/numspy-api) </br>
NumSpy-Android App : [https://github.com/vkoshti/numspy-app](https://github.com/vkoshti/numspy-app) </br>
NumSpy-React App   : [https://github.com/bhattsameer/numspy-react-app](https://github.com/bhattsameer/numspy-react-app)

# Credits:
Thanks to Way2sms.</br>
Logo : [Hariom Panchal](https://github.com/Hariompanchal)
