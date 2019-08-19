<p align="center">
    <a href="https://smartproxy.com/"><img src="https://smartproxy.com/wp-content/themes/smartproxy/images/smartproxy-logo.svg" alt="Smartproxy logo" width="200" height="50"></a>
  </a>
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

<img src="https://content.screencast.com/users/JohanSP/folders/Jing/media/87b3ab19-cdb2-4e2b-ae8a-9431f538ee9a/smartproxy-beautifulsoup-configuration.png" alt="curl smartproxy beautifulsoup http proxy configuration">

You should now see your project folder populated with *beautifulsoup.py* file.

### Configuration

To start using our example script, all you need to do is to configure the lines below.

Endpoint:
```
proxies = {'https': 'https://gate.smartproxy.com:7000'} # Your desired endpoint within punctuation marks ('')
```
Username and password:
```
auth = requests.auth.HTTPProxyAuth('username','password') # Your username and password for proxy authentication
```

<img src="https://i.imgur.com/wbTPbx5.png" alt="smartproxy beautifulsoup http proxy configuration with username password authentication">

### Usage

To execute the example, simply run python command:

```
python beautifulsoup.py
```

If everything was done correctly, you should be seeing the output as proxy IP:

<img src="https://i.imgur.com/yglY5EA.png">

## Need help?
Email - sales@smartproxy.com
<br><a href="https://smartproxy.com">Live chat 24/7</a>
