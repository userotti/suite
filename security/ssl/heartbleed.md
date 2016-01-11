Heartbleed (officially known as CVE-2014-0160) is a security vulnerability in the OpenSSL cryptographic library. The bug allows anyone online to read the memory of vulnerable systems using OpenSSL, effectively compromising the keys used to secure the traffic between client and server.

# How do I fix this?

You'll just need to install any available security updates for your operating system or runtime environment. If you're using a co-hosting environment, this will be up to whoever is responsible for administration. Immediately notify the administrators of your environment if this applies to you. If unable to apply updates to your system, it's possible to recompile OpenSSL without the handshake feature by using the compile time option `-DOPENSSL_NO_HEARTBEATS`.

# Resources

* [heartbleed.com](http://heartbleed.com/)
* [OpenSSL Security Advisory](https://www.openssl.org/news/secadv/20140407.txt)
* [MITRE](http://cve.mitre.org/)
