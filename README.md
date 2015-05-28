# Transmission-WFUI

Web Flat UI for Transmission

## Description

Transmission-WFUI is a simplified interface to Transmission. I cleaned many features and got flat design :)

## Installation

This UI is based on Transmission 2.84 running on Debian 8

First, save the original UI with :

```sh
$ mv /usr/share/transmission/web/ /usr/share/transmission/web.old/
```

Then, download the new UI :

```sh
$ git https://github.com/Kalizo/Transmission-WFUI.git /usr/share/transmission/web/
```

Finally, refresh Transmission :

```sh
$ sudo service transmission-daemon reload
```

## Credits

* Font Awesome
* Flat UI Colors
* Foundation
* Google Fonts
