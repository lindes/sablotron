This is the README file for the XSL processor called Sablotron

0. About Sablotron on Github
1. What is it Sablotron?
2. Licensing
3. Warranty
4. Porting
5. Installation
6. Sablotron and Perl
7. More info

0. About Sablotron on Github
========================================

This is just a manually-updated mirror of
[sablotron](http://sourceforge.net/projects/sablotron/), created to
allow me to more easily track changes I might want to make, and for
the world to have the option of benefiting from them, if they're
useful.  Forked by David Lindes, 2012-05, from 1.0.3.


1. What is Sablotron?
========================================

Sablotron is an XML processor fully implemented in C++. It uses Expat by
James Clark as an XML parser. Sablotron implements XSLT 1.0, XPath 1.0 
and DOM Level2.

Original creator of Sablotron is Ginger Alliance (www.gingerall.com).


2. Licensing
========================================

Sablotron is an Open Source project released under the MPL (Mozilla Public 
License). Alternatively you may use Sablotron under the GNU's GPL license.

Please, look at http://www.mozilla.org/MPL or
http://www.gnu.org/copyleft/gpl.html for further info.

If you want use the debugger, you may optionally ask Sablotron to use
the GNU readline library. Since this library is available under GPL
only, you have to confirm, that you are accepting the GPL for the
whole Sablotron library. You can do it, if you set the SABLOT_GPL=1
environment during the configure process.

3. Warranty
========================================

We offer NO WARRANTY for using Sablotron in any conditions.


4. Porting
========================================

So far Sablotron is tested on Linux (RedHat 5.2, 6.0, 6.1, 6.2, 7.0,
8.0 and 9), Windows (NT 4.0, 95, 98, 2000), Solaris (2.5.1, 2.6, 7), 
HP-UX (11.00), FreeBSD (3.4, 4.1), OpenBSD (2.8 beta) and OpenServer
(5.0.x). We hope, that it should work on most other Unix systems as well.

If you build Sablotron on some other system, please, let us
know. All porting activities are welcome.


5. Installation
========================================

To build and run Sablotron read the INSTALL file in the same
directory as this file.

To install or compile Sablotron on Windows read the INSTALL_WIN
file instead.


6. Sablotron and Perl
========================================

If you'd like to call Sablotron from Perl, download the XML::Sablotron
module from our website (http://www.gingerall.org) or from CPAN.

Follow the instructions from the README and INSTALL files of the Perl package.


7. More info
========================================

For more info (including Sablotron manual and API reference) look at
the Ginger Alliance web site:

http://www.gingerall.org

Maillist subscriptions are also available on this site.


Enjoy Sablotron!!

GA
