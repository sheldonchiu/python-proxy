# Python Proxy Server
> No third party libraries that provide HTTP or proxy support is used in this project

Aviliable Functions:
+ Multithreading
+ Forwarding HTTP requests
+ Forwarding HTTPS requests
+ Access control by filtering domain name
+ Caching of both HTTP and HTTPS response according to RFC

**Only tested on Linux system (Ubuntu 18.04)**

Step:
1. Run the notebook
2. Change the proxy setting in firefox (default port: 12345)
3. Head to www.proxy.test to download the CA cert
4. Add domain name to the blackList variable if needed
5. Feel free to make any changes to the notebook 