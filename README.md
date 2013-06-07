RObrew
======

# What is RObrew?

It's a Linux (Debian Based OS / Red Hat Based OS) application that will provide you a simple life in ragnarok emulator management.

Example without RObrew:

You need to install package dependencies to your emulator manually, for example:

    * gcc
    * make
    * mysql
    * mysql-devel
    * mysql-server
    * pcre-devel
    * subversion
    * zlib-devel

And then download the emulator from svn/repo and compile it!

# Example with RObrew:

After install RObrew you just need to do that command in your terminal:

    $ robrew install <emulator>

### To install eAthena:

    $ robrew install eathena

### To install rAthena:

    $ robrew install rathena

### To install Hercules:

    $ robrew install hercules

Package Dependencies:
 
    * gcc
    * make
    * mysql
    * mysql-devel
    * mysql-server
    * pcre-devel
    * subversion
    * zlib-devel

The robrew command will install all package dependencies automatically, download <emulator> from official svn/repository.

If you want to compile:

    $ robrew compile /path/to/downloaded/<emuator>/folder/

RObrew is now in development and the first release will have plugins. For example, a plugin named emulator-dropbox-backup that provide automatically daily backups from your emulator and database to a DropBox storage.

if you are interested to get involved contact me (PM).

Thanks! Let's make the world better 

with Love <3,
c0nsumer (Filipe Barros)
