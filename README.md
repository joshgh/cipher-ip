# Cipher

#### Encrypt and decrypt a message, 2016 December 02

#### By Josh Huffman

## Description

This is a website built in Drupal demonstrating custom modules. It includes a cipher module which creates pages to allow a user to encode and decode secret messages.

## Setup/Installation Requirements

Must have a web server running with MySQL and PHP installed. This installation varies across systems, one option is to use MAMP or WAMP, instructions are available at [learnhowtoprogram](https://www.learnhowtoprogram.com/drupal/getting-started-with-drupal/server-and-database-setup).

Make sure you have git installed on your computer.
Run `git clone https://github.com/joshgh/cipher-ip`

Import the database dump located in bookstore-ip/sites/db-backup to your mysql server, the easiest method is using phpmyadmin.

Create a mysql user with access to this database, the current site configuration uses username:cipher/ password:cipher

If your mysql server uses a port other than 8889 make sure to change that in bookstore-ip/sites/default/settings.php

Start your webserver with the document root pointing to bookstore-ip

Visit localhost in your browser, if the server uses a port other than 80 make sure to specify that in the URL (localhost:portnumber)

## Support and contact details

Contact me at j.m.huffman@gmail.com with any comments or questions.

## Technologies Used

This site was build using Drupal.

### License

MIT License

Copyright (c) 2016 **Josh Huffman**
