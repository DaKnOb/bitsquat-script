#bitsquat-script
**Bitsquat Domain Generation Script**
<hr/>


## Overview

Use bitsquat-script to generate a valid list of domain names based on a target that have chances to get some traffic via the Bitsquating problem. For more information on what this is, read [this article](http://dinaburg.org/bitsquatting.html) or watch this [YouTube video](http://www.youtube.com/watch?v=lZ8s1JwtNas).

## Features

* Generate a list of valid domain names capable of bitsquating an original one
* Check the availability of the domain names generated[^1]

[^1]: This function is based on whether a DNS query to that domain actualy resolves an IP address to connect to. Domains without a DNS configuration may appear as available.

## Usage
_Please note that you need Python installed for this to work_

```Shell
python bitsquat.py example .com
```
<br/><br/>
_bitsquat.py_ being the file name,<br/>
_example_ being the domain name,<br/>
_.com_ being the domain suffix



** Latest update: September 14, 2013**