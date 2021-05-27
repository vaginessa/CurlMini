# CurlMini | [Latest release](https://github.com/Zalexanninev15/CurlMini/releases/tag/1.2.5)

![alt](https://github.com/Zalexanninev15/CurlMini/blob/master/Logo.png?raw=true)

[![](https://img.shields.io/badge/OS-Windows-informational?logo=windows)](https://github.com/Zalexanninev15/CurlMini)
[![](https://img.shields.io/github/v/release/Zalexanninev15/CurlMini)](https://github.com/Zalexanninev15/CurlMini/releases/latest)
[![](https://img.shields.io/github/downloads/Zalexanninev15/CurlMini/total.svg)](https://github.com/Zalexanninev15/CurlMini/releases)
[![](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![](https://img.shields.io/badge/donate-QIWI-FF8C00.svg)](https://qiwi.com/n/ZALEXANNINEV15)
[![](https://img.shields.io/badge/donate-YooMoney-8B3FFD.svg)](https://yoomoney.ru/to/410015106319420)

## Screenshot

![alt](https://github.com/Zalexanninev15/CurlMini/blob/master/CurlMini-Screenshot.png)

## Description
Graphical version of the curl utility for Windows 7-10

## System requirements
* **OS:** Windows 7/8/8.1/10
* **Additional:** Microsoft .NET Framework 4.5, curl (if this utility is not available, you will be prompted to install it in automatic mode)

## Features

* Fast execution of curl requests
* The last executed request is saved in the history and automatically inserted into the text field for the requests to be executed again later
* Unique feature of installing curl utility on all versions of Windows (7-10)
* The ability to expand the text field for the command so that you can check the request for indents, unnecessary spaces, or even line breaks, which of course will affect the performance of the command
* The result of the curl utility is recorded in text fields, and the results can be compared "right in front of your eyes"
* Commands are recorded in the "requests history" and then they can be reused. The list is also saved in a file called "requests.log"
* The utility performs smart checks and displays progress statuses of work

## How to use it?

### GIF: 

[See here](https://github.com/Zalexanninev15/CurlMini/blob/master/CurlMini-Example.gif)

### Text:

1. Launch the utility and make sure that your version of Windows 10 is higher or equal to build 1803. **This is very important!**

2. Enter/paste the desired command in the "Requests:" text field (the command must be written/inserted without "curl" at the beginning). 

**For example:**

*The original request:* 

```bash
curl -F shorten=https://www.youtube.com/ https://0x0.st
```

*The text you need:*

```bash
-F shorten=https://www.youtube.com/ https://0x0.st
```

3. Click the "Send request" button and wait for the process to finish. Text fields with results will be automatically updated at the end of the process.

## Build
Compile using Visual Studio 2015-2019, tested on Visual Studio 2019
