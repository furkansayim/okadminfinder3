![](https://rawcdn.githack.com/mIcHyAmRaNe/okadminfinder3/ce4eaa2c8a322f4313816d2252b6ac4bc8dc5409/Classes/okadminfinder3-.svg)

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/Django.svg)
[![GitHub license](https://img.shields.io/github/license/mIcHyAmRaNe/okadminfinder3.svg)](https://github.com/mIcHyAmRaNe/okadminfinder3/blob/master/LICENSE)
![](https://img.shields.io/badge/platform-linux%20%7C%20windows%20%7C%20osx-lightgrey.svg)
[![GitHub stars](https://img.shields.io/github/stars/mIcHyAmRaNe/okadminfinder3.svg?style=social)](https://github.com/mIcHyAmRaNe/okadminfinder3/stargazers)

## OKadminFinder: Easy way to find admin panel of site

*OKadminFinder is an Apache2 Licensed utility, rewritten in **Python 3.x**, for admins/pentesters who want to find admin panel of a website. There are many other tools but not as effective and secure. Yeah, Okadminfinder has the the ability to use tor and hide your identity*

* ## Requirements
    ![PyPI](https://img.shields.io/pypi/v/argparse.svg?label=argparse)
    ![PyPI](https://img.shields.io/pypi/v/colorama.svg?label=colorama)
    ![PyPI](https://img.shields.io/pypi/v/PySocks.svg?label=PySocks)
    ![PyPI](https://img.shields.io/pypi/v/tqdm.svg?label=tqdm)
    ![PyPI](https://img.shields.io/pypi/v/requests.svg?label=requests)
    * #### Linux
       ```
       sudo apt install tor
       sudo apt install python3-socks  (optional)
       pip3 install --user -r requirements.txt
       ```

    * #### Windows
       download [tor expert bundle](https://dist.torproject.org/torbrowser/8.0.8/tor-win32-0.3.5.8.zip)
       `pip3 install -r requirements.txt`

* ## Usage
    * #### Preview
       [![asciicast](https://asciinema.org/a/209959.png)](https://asciinema.org/a/209959)

    * #### Linux
       ```
       git clone https://github.com/mIcHyAmRaNe/okadminfinder3.git
       cd okadminfinder3
       chmod +x okadminfinder.py
       python3 okadminfinder.py
       ```

    * #### Windows
       download & extract [zip](https://github.com/mIcHyAmRaNe/okadminfinder3/archive/master.zip)
       ```
       cd okadminfinder3
       py -3 okadminfinder.py
       ```

    * #### [Pentestbox](https://pentestbox.com) (same procedure as Linux)
        you can add an alias by adding this line: `okadminfinder=py -3 "%pentestbox_ROOT%/bin/Path/to/okadminfinder3/okadminfinder.py" $*` to `C://Pentestbox/bin/customtools/customaliases` file and so you'll be able to launch it using      `okadminfinder`
      
    * ### Docker Build

         ```
         $ docker build -t xshuden/okadminfinder .
         ```

    * ### Docker Usage

         ```
         $ docker run --rm -it xshuden/okadminfinder
         $ docker run --rm -it xshuden/okadminfinder -u google.com
         ```

## Features
- [x] More than 500 potential admin panels
- [x] Tor & Proxy
- [x] Random-agents
- [x] Console work with params, like: `okadminfinder.py -u example.com --proxy 127.0.0.1:8080`
- [ ] Classify [admin panel links](https://github.com/mIcHyAmRaNe/okadminfinder3/blob/master/LinkFile/adminpanellinks.txt) by popularity
- [ ] Multithreading, for faster work
- [ ] Adding more potential admin panel pages

## Youtube videos
- [okadminfinder : admin page finder](https://youtu.be/DluCL4aA9UU/)
- [okadminfinder3 : admin page finder (update)](https://youtu.be/iJg4NJT5qkY/)
- [admin panel finder Kali Linux 2018.3](https://youtu.be/kY9KeDqY5QQ)
