![Logo](admin/onvif-alt.png)
# ioBroker.onvif-alt

[![NPM version](http://img.shields.io/npm/v/iobroker.onvif-alt.svg)](https://www.npmjs.com/package/iobroker.onvif-alt)
[![Downloads](https://img.shields.io/npm/dm/iobroker.onvif-alt.svg)](https://www.npmjs.com/package/iobroker.onvif-alt)
[![Dependency Status](https://img.shields.io/david/jey-cee/iobroker.onvif-alt.svg)](https://david-dm.org/jey-cee/iobroker.onvif-alt)
[![Known Vulnerabilities](https://snyk.io/test/github/jey-cee/ioBroker.onvif-alt/badge.svg)](https://snyk.io/test/github/jey-cee/ioBroker.onvif-alt)

[![NPM](https://nodei.co/npm/iobroker.onvif-alt.png?downloads=true)](https://nodei.co/npm/iobroker.onvif-alt/)

**Tests:**: [![Travis-CI](http://img.shields.io/travis/jey-cee/ioBroker.onvif-alt/master.svg)](https://travis-ci.org/jey-cee/ioBroker.onvif-alt)

# Development stopped
From now on this adapter does not become any new features, features that aren't completed yet will not be finalized.
But i will provide fixes to keep it compatible with future versions of ioBroker.

## Onvif - IP camera protocol

The aim of this adapter is to find and control cameras that supports the Onvif protocol

## Manual

1. Install adapter and start instance. 
After a while (~30 seconds) all cameras on your network should be found and objects are created.
2. Then go to Instance configuration and enter the credentials for the cameras. Leave IP and Port unchanged.
3. It takes some time to connect with cameras and get all capabilities of the cameras.


## Changelog

### 0.2.0
* rename adapter

### 0.1.3
* (jey-cee) add cameras manual

### 0.1.2
* (jey-cee) 2nd try check for NetworkVideoTransmitter
* (jey-cee) add continuous move for PTZ
* (jey-cee) add delete Presets
* (jey-cee) add create new Preset
* (jey-cee) add update Preset (needs verification from other users)

### 0.1.1
* (jey-cee) check for NetworkVideoTransmitter
* (jey-cee) connect to cams without credentials
* (jey-cee) fix getlogs
* (jey-cee) fix getNetworkProtocols
* (jey-cee) fix getNetworkInterfaces
* (jey-cee) show Audio Outputs in log only, WIP help needed
* (jey-cee) read and execute presets

### 0.1.0
* (jey-cee) fixed get system log
* (jey-cee) fixed reboot
* (jey-cee) scanWifi added, function WIP
* (jey-cee) make PTZ movement work

## License
MIT License

Copyright (c) 2019 Jey Cee <jey-cee@live.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.