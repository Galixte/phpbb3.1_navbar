# phpBB 3.1 Extension - Navigation Buttons

## Installation

Clone into phpBB/ext/vipaka/navbar:

    git clone https://github.com/nickvergessen/phpbb-ext-acme-demo.git phpBB/ext/acme/demo

Go to "ACP" > "Customise" > "Extensions" and enable the "Navigation Buttons Extension" extension.

## Tests and Continuous Integration

We use Travis-CI as a continous integration server and phpunit for our unit testing. See more information on the [phpBB development wiki](https://wiki.phpbb.com/Unit_Tests).
To run the tests locally, you need to install phpBB from its Git repository. Afterwards run the following command from the phpBB Git repository's root:

Windows:

    phpBB\vendor\bin\phpunit.bat -c phpBB\ext\vipaka\navbar\phpunit.xml.dist

others:

    phpBB/vendor/bin/phpunit -c phpBB/ext/vipaka/navbar/phpunit.xml.dist

[![Build Status](https://travis-ci.org/nickvergessen/phpbb-ext-acme-demo.png?branch=master)](https://travis-ci.org/nickvergessen/phpbb-ext-acme-demo)

## License

[GPLv2](license.txt)
