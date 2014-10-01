## Download

Download this repository using the following command:

	git clone --recursive https://github.com/fredrikcarno/flyerpic.git
	
## Installation

### 1. Install Lychee

Install Lychee using the public documentation from [GitHub](https://github.com/electerious/Lychee/blob/master/docs/Installation.md).
	
### 2. Edit .htaccess

Open the `.htaccess` from the root of Lychee and uncomment the lines to allow access from different origins. This allows the Backend to work with the API of Lychee.

### 3. Enable public mode in Lychee

> Not documented, yet

### 4. Install watermark-plugin 

Install lychee-watermark using the public documentation from [GitHub](https://github.com/electerious/lychee-watermark).

### 5. Install Frontend

Install the Frontend next to the Lychee-folder using the `readme.md` in the folder of the Frontend.

### 6. Install ZBar

Install [ZBar](http://zbar.sourceforge.net). Check if the command `zbarimg` is working in the command-line after the installation.

	sudo apt-get install zbar-tools

### 7. Install Poppler

Install [Poppler](http://poppler.freedesktop.org). Check if the command `pdfunite` is working in the command-line after the installation.

	sudo apt-get install poppler-utils
	
### 8. Install PhantomJS

Install [PhantomJS](http://phantomjs.org).

	npm install -g phantomjs

### 9. Install Backend

Install the Backend next to the Lychee-folder using the `readme.md` in the folder of the Backend.