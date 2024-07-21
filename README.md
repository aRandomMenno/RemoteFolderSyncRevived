
> I've currently only made changes to the readme, I plan to (almost) completely rewrite the entire python script.

# RemoteFolderSync Python

- Original Credits to [Stefansundin](https://github.com/stefansundin/remotefoldersync)!

## Instructions

1. Install Install the lastest Python version
2. Install [pycrypto](http://www.voidspace.org.uk/python/modules.shtml#pycrypto).
3. You need a custom paramiko since the normal doesn't have Python3 support. `git clone https://github.com/nischu7/paramiko.git`
4. `python setup.py build`
5. Copy `build\lib\paramiko` to `C:\Python33\Lib\paramiko`.
