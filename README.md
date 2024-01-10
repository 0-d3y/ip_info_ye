![Logi](https://files.catbox.moe/38jvnb.png)

# IP INFO

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.6%2B-blue.svg)](https://www.python.org/downloads/release)
[![GitHub issues](https://img.shields.io/github/issues/mr-sami-x/ip_info_ye)](https://github.com/mr-sami-x/ip_info_ye/issues)
[![GitHub stars](https://img.shields.io/github/stars/mr-sami-x/ip_info_ye)](https://github.com/mr-sami-x/ip_info_ye/stargazers)

## Overview

ip info is an advanced artificial intelligence library designed to assist with the development of sophisticated and efficient software solutions.

## Features

- Show accurate information
- Location information on GPS
- Network information

## Installation

You can install ip-info-ye using pip:

```
pip install ip-info-ye
```

## Example:
```
from ip_info_ye import ip_info
import json

ip_address = "8.8.8.8"
ip_info_ye= ip_info(ip_address)
print(json.dumps(ip_info_ye, indent=2))
```
