# Eadui-Font
Script font based on the work of the eleventh-century scribe Eadui Basan

![Eadui specimen](http://oldenglishaerobics.net/images/specimen01.png)

Version 1 of this Open Source font (SIL Open Font License) was released via the Open Font Library
(www.openfontlibrary.org). Version 2, now under development, features improved outlines and completely
reworked OpenType tables. It is being developed with FontForge and the Adobe FDK.

To build the OTF version of the font under Linux or OS X, make sure FontForge and the Adobe FDK tools
are in your path, and then type

./mkfont Eadui

The simple mkfont script will call FontForge to generate the font and the Adobe tools to add hints and
OpenType features. There is not yet a script to generate the TTF version.
