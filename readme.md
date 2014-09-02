### 1. Install Lychee

Install Lychee using the public documentation from [GitHub](https://github.com/electerious/Lychee/blob/master/docs/Installation.md).
	
### 2. Edit .htaccess

Open the `.htaccess` from the root of Lychee and uncomment the lines to allow access from different origins. This allows the Backend to work with the API of Lychee.

### 3. Enable public mode in Lychee

> Not documented, yet

### 4. Install watermark-plugin 

Install lychee-watermark using the public documentation from [GitHub](https://github.com/electerious/lychee-watermark).

### 5. Install lychee-redirect

Install lychee-redirect using the public documentation from [GitHub](https://github.com/electerious/lychee-redirect).

### 6. Install miniLychee

Install miniLychee next to the Lychee-folder using the `readme.md` in the folder of miniLychee.

### 7. Install libqrencode

Install `libqrencode` C library. This dependency is used by [node-qr](https://github.com/bcelenza/node-qr) which includes a documentation on how to install the library.

	sudo apt-get install qrencode

### 7. Install ZBar

Install [ZBar](http://zbar.sourceforge.net). Check if the command `zbarimg` is working in the command-line after the installation.

	sudo apt-get install zbar-tools

### 8. Install Poppler

Install [Poppler](http://poppler.freedesktop.org). Check if the command `pdfunite` is working in the command-line after the installation.

	sudo apt-get install poppler-utils

### 9. Install Backend

Install the Backend next to the Lychee-folder using the `readme.md` in the folder of the Backend.