<p align="center">
<a href="https://dashboard.smartproxy.com/?page=residential-proxies&utm_source=socialorganic&utm_medium=social&utm_campaign=resi_trial_GITHUB"><img src="https://i.imgur.com/opsHIEZ.png"</a>
</p>

<p align="center">
    <a href="https://github.com/Smartproxy/Smartproxy"> :house: Main Repository :house: </a>
</p>

### Disclaimer

The following example provides you with a basic request using a proxy to a specific website, if you want to learn more about Beautiful Soup, make sure to check their documentation [here](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#quick-start).

### Prerequisites

To run our example script, you are going to need a few Python libraries as well as Python 3.7.x itself with Beautiful Soup 4.

* [Python](https://www.python.org/downloads/)
* [Beautiful Soup 4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup)
* [Python's Requests Library](https://realpython.com/python-requests/)
* [lxml](https://lxml.de/installation.html)

### Installation

Once you have all the prerequisites ready, enter your project folder or create a new one.

<img src="https://i.imgur.com/RaLIVjy.png">
<img src="https://i.imgur.com/1TeL3xI.png">

When project directory is setup, you can download our script:

`curl https://raw.githubusercontent.com/Smartproxy/BeautifulSoup/master/beautifulsoup.py > beautifulsoup.py`

<img src="https://i.imgur.com/nE2ANuV.png" alt="curl smartproxy beautifulsoup http/https proxy configuration">

You should now see your project folder populated with *beautifulsoup.py* file.

### Configuration

To start using our example script, all you need to do is to configure the lines below.

Proxy username, password and endpoint:
```
proxies = {'http': 'http://username:password@gate.smartproxy.com:7000', # Your username, password for proxy authentication, and desired endpoint within punctuation marks ('')
          'https': 'http://username:password@gate.smartproxy.com:7000'} 
```

<img src="https://i.imgur.com/xUB7Q6s.png" alt="smartproxy beautifulsoup http/https proxy configuration with username password authentication">

### Usage

To execute the example, simply run python command:

```
python beautifulsoup.py
```

If everything was done correctly, you should be seeing the output as proxy IP:

<img src="https://i.imgur.com/7vNWqRi.png">

## Need help?
Email - sales@smartproxy.com
<br><a href="https://smartproxy.com">Live chat 24/7</a>
