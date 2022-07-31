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
