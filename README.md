## About
Cross-compiled in Ubuntu 16.04 using Mingw. Static build.  
Libraries:
- Zlib 1.2.8
- OpenSSL 1.1.1q
- Libevent 2.1.11

Compatibility with Windows XP is provided by the [One Core API libraries](https://github.com/Skulltrail192/One-Core-API-Binaries/).

## Usage
See torrc file in the archive. It includes examples. Run: `start.bat`  
Please note: Tor is blocked in some countries, in that case use obfs4 bridges.  
XP build will not work on other Windows.  
Please report XP bugs in my Issues.

To use a Tor proxy, specify in your browser or other application:  
Proxy: socks5 127.0.0.1, port 9050, DNS through proxy.

## Bugs
Due to patching and/or One Core API the XP build doesn't work with the obfs4proxy pluggable transport.  

If you need obfs4proxy, use the latest official Tor build for XP [0.4.4.6](https://archive.torproject.org/tor-package-archive/torbrowser/10.0.11/tor-win32-0.4.4.6.zip) from 12 Nov 2020.  
There is also a [0.4.4.9](https://github.com/torproject/tor/releases/tag/tor-0.4.4.9) backport from 14 Jun 2021, but it is only available as source code.
