# vela_public
web crawler + Sensitive Information Identification

## Features

* [x] Web Crawler<br/>
* [x] ID Card, phone, <br/>
* [x] Web Directory Brute<br/>
* [] Custom brute dictionary (todo) <br/>

## Examples
URL Input
```
vela -t http://example.com
```

Multiple URLs Input (comma-separ)
```
vela -t http://example.com,http://scanme.nmap.org,http://vulnweb.com
```

List of URLs Input
```
$ cat url_list.txt

http://example.com
http://scanme.nmap.org
..
```

```
vela -T url_list.txt
```

Enable Brute
```
vela -t http://example.com -b
```

## Download
<a href="https://github.com/zan8in/vela_public/releases">Release</a>