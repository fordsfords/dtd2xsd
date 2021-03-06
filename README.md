# dtd2xsd

## What?

The [dtd2xsd.pl](dtd2xsd.pl) tool was obtained from
https://www.w3.org/2000/04/schema_hack/ on 27-Dec-2018.
I took a snapshot of that page which can be found in the file
[DTD2Schema.html](DTD2Schema.html), and which can be rendered at:
https://fordsfords.github.io/dtd2xsd/DTD2Schema.html
My copy is only an archive/snspshot; please go to the
[original page](https://www.w3.org/2000/04/schema_hack/) for its
official content.

As of 27-Dec-2018, that page lists the copyright as follows:

The program is Copyright © W3C® and provided under the
[W3C Software License](https://www.w3.org/Consortium/Legal/copyright-software).

I put the text of that license page as of 27-Dec-2018 into
[LICENSE.txt](LICENSE.txt).

## Why?

I ported dtd2xsd to GitHub because I wanted some changes and it doesn't
seem very likely that after 18+ years of no attention the W3C will
update the official copy.  :-)

* Most importantly, enhanced tool to allow more than one attribute
for an element.  (Oddly, the tool already had logic to do it, but it
was not used.)

* Changed the [shebang](https://en.wikipedia.org/wiki/Shebang_(Unix))
to "#!/usr/bin/env perl" so that it looks up the Perl interpreter via
the user's PATH.

* Made successful execution silent (i.e. removed "Open mapping ... successful"
message).
