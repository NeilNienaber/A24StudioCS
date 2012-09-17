# A24Studio Code Sniffer Coding Standards

This project contains the coding standard rule to be used in PHP Code sniffer for any
project owned by A24Studio.

The standards are derived of PSR 0, 1 and 2 standards with additional checks on php docblock
comments.

# Dependencies

This coding standard is dependend on the PSR coding standards, the Generic standards, Zend coding standards
and PEAR coding standards. All these, except the PSR coding standards, are installed by default.

The PSR Coding standards can be found [here](git://github.com/klaussilveira/phpcs-psr.git). To install the PSR coding standards, I recommend following the commands below:
```bash
 cd /usr/share/php/PHP/CodeSniffer/Standards
 sudo git clone https://github.com/klaussilveira/phpcs-psr PSR
``

This will install the PSR coding standards on the system, but will not set them as the default.

# Installation

To install the coding standards, do the following:
```bash
cd /usr/share/php/PHP/CodeSniffer/Standards
sudo git clone git@github.com:jaconel/A24StudioCS.git
```

To set the A24Studio coding standards as the defaults, execute the following code:
```bash
sudo phpcs --config-set default_standard A24StudioCS
```
