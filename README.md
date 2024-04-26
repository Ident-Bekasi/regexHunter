
# regexHunter

regex Hunter- Fast website endpoint sensitive data scraper

The tool in question was created in javascript (node js), python and shell scripting and its main objective is to search for sensitive data and API keys in JavaScript files and HTML pages.


## File Tracture

One Directory after there must be a list of website file need.

```bash
  ├── gospider_domain_list
└── regexHunter(tols)
    ├── package.json
    ├── package-lock.json
    ├── run.sh
    └── tools.js

```


## Features

- Super Faster



## Requirement
- node js
- python
- [GoSpider Tools](https://github.com/jaeles-project/gospider)



## Usage

```bash
 (                       )                          
 )\ )                 ( /(               )          
(()/((  (    (    )   )\())  (        ( /(  (  (    
 /(_))\))(  ))\( /(  ((_)\  ))\  (    )\())))\ )(   
(_))((_))\ /((_)\())  _((_)/((_) )\ )(_))//((_|()\  
| _ \(()(_|_))((_)\  | || (_))( _(_/(| |_(_))  ((_) 
|   / _` |/ -_) \ /  | __ | || | ' \))  _/ -_)| '_| 
|_|_\__, |\___/_\_\  |_||_|\_,_|_||_| \__\___||_|   
    |___/                                           


Author: @SecurityTalent
join_us: https://t.me/Securi3yTalent
 
Usage: ./run.sh <input_file1> [<input_file2> ...] ** Fast need to sorting url's
Usage: ./run.sh [-h] [-t] [-s] [-i]      example:  run.sh -t | run.sh -s | run.sh -i

Options:
  -h, --help       Display this help message
  -t               Identify the technology used by websites
  -s               Find the endpoint sensitive data
  -i               Convert domains to IP addresses and save to file



```


Fast need clone the repo
```bash
git clone https://github.com/securi3ytalent/regexHunter.git
```

```bash
cd regexHunter
```
Dependency install
```bash
npm i
```

sorting the url's
```bash
./run.sh < gospider_list_file  >
```
Find the endpoint sensitive data and API
```bash
./run.sh -s
```
Identify the technology
```bash
./run.sh -t
```
Convert domains to IP addresses
```bash
./run.sh -i
```



## Buy me a coffee?
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/securitytalent)