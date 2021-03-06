AutoBrowser Screenshot
===========

AutoBrowser screenshot is a tool written in python language that used for penetration testing.
The purpose of this tool is to parse nmap (Port scanner) results or just a simple text file that contain ip addresses and ports (for example http://127.0.0.1:31337)
and send a http/s request to each live host with his open port number using popular Web Browsers such as:

* Internet Explorer
* Mozilla Firefox
* Google Chrome
* Safari

AutoBrowser grabs a screenshot of the response page content.
This tool is designed for IT professionals to perform penetration testing and analyzing NMAP results.
The tool can analyze text files as well as links to separate lines.
This tool checks whether a specific port address is tested (tested in HTTP and in HTTPS) so they can make their test which make our lives easier (no hard work!).

[Proof of concept video](https://www.youtube.com/watch?v=iiexvh3KLvE&feature=youtu.be)
Requirements:
===============
###Linux Installation:
1. sudo apt-get install python-dev python-pip
2. sudo pip install -r requirements.txt

###MacOSx Installation:
1. Install Xcode Command Line Tools (AppStore)
2. sudo easy_install pip
3. sudo pip install -r requirements.txt

###Windows Installation:
1. Install [docopt](https://github.com/docopt/docopt)
2. Install [requests](http://www.lfd.uci.edu/~gohlke/pythonlibs/#requests)
3. Install [lxml](http://www.lfd.uci.edu/~gohlke/pythonlibs/#lxml)
4. Install [selenium](https://pypi.python.org/pypi/selenium)
5. Install [futures](https://pypi.python.org/pypi/futures)
6. Open Command Prompt(cmd) as Administrator -> Goto python folder -> Scripts (cd c:\Python27\Scripts)
7. pip install -r (Full Path To requirements.txt)

Credits
========
* Avi Orenstein
* Tomer Zait
