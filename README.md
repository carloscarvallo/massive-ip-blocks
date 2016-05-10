## ******************************* Beta Version *******************************

[![bitHound Overall Score](https://www.bithound.io/github/carloscarvallo/massive-asn-blocks/badges/score.svg)](https://www.bithound.io/github/carloscarvallo/massive-asn-blocks)
[![bitHound Code](https://www.bithound.io/github/carloscarvallo/massive-asn-blocks/badges/code.svg)](https://www.bithound.io/github/carloscarvallo/massive-asn-blocks)

# Massive ASN blocks

[![Join the chat at https://gitter.im/carloscarvallo/massive-asn-blocks](https://badges.gitter.im/carloscarvallo/massive-asn-blocks.svg)](https://gitter.im/carloscarvallo/massive-asn-blocks?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
CLI Tool in Node for scan over requested ASN's Blocks

### Install
**recommended install globaly:**
``` bash
$ npm install asn-blocks -g
```

### Usage
```
Usage: asn-blocks [options]

Options:

  -h, --help            output usage information
  -V, --version         output the version number
  -c, --command <args>  Command to be executed

```

### Examples:
``` bash
$ asn-blocks -c "nmap -n -P0 -vvv <ip>/<range>"
$ asn-blocks -c "smbclient -L <ip> -U%"
```
  Where `<ip>` or `<range>` where be replaced for the values of the choosen block

**command executed will be:**
``` bash
$ nmap -n -P0 -vvv 190.168.0.1/24
$ smbclient -L 190.168.0.1 -U%
```
### ToDo

```
- Add more providers
- Improve errors and usage
- Handle pid process kill
```

*****************************************************************
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.
*****************************************************************
![image](http://www.gnu.org/graphics/gplv3-88x31.png)
 © 2015-2016 Carlos Carvallo
