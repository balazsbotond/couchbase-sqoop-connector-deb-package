Debian package for Couchbase Sqoop Connector
============================================

A Debian package for installing Couchbase Sqoop Connector for Apache Sqoop 1.4.6. Works on Ubuntu.

**Download the latest pre-built release here:**
https://github.com/balazsbotond/couchbase-sqoop-connector-deb-package/releases

Building the package
--------------------

Clone the repository:

    git clone https://github.com/balazsbotond/couchbase-sqoop-connector-deb-package.git

Build the package using `dpkg-deb`:

    dpkg-deb --build couchbase-sqoop-connector-deb-package-1

This will create a `couchbase-sqoop-connector-deb-package-1.deb` file in the current directory.

Installing the package
----------------------

    dpkg -i couchbase-sqoop-connector-deb-package-1.deb
    apt-get install -f

