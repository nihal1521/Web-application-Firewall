# WAF WAF V1.1

<hr>

WAF WAF is an open-source advanced web application firewall that works with a smart and new detection technology, achieving 99% of precise answers!<br>
With an interactive CLI you can easily scan weaknesses on your local network, configure WAF WAF, and see what is happening on your server.

## Installation
You are able to use WAF WAF on both, your local machine and [docker](https://docs.docker.com/).

### Local Machine
After downloading WAF WAF, you first need to run the following command to install requirements:
```bash
pip install -r requirements.txt
```
After running the command, you will be able to run WAF WAF.

### Docker
Use the following command to install WAF WAF from docker:
```bash
docker pull wafwafdetective/waf_waf:V1.1
```


## Features & Technology
At the end of each day, an email attached with a detailed log will be sent, containing information about all the attempted attacks on the server.<br>

WAF WAF Version 1.1 is capable of protecting servers from the following attacks:
- Brute Force
- Command Injection
- File Inclusion
- SQL Injection
- XSS
- XXE
