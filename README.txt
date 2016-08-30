LLVM WWW Pubs
=============

This directory contains a list of publications surrounding LLVM technology and
is completely voluntary, ie. authors have to submit their own papers, as there
is no web crawling involved.

Adding a new paper
------------------

To add a new paper, just copy and paste the format of the top-most paper in
pubs.js and change the fields. The JavaScript code at the end will make sure
they get displayed correctly and also will update the histogram that appears on
the page.

Adding a new year
-----------------

When you add a new paper from a year that wasn't there, the histogram will not
show it, because the width is hard-coded. To change that, increase the image's
horizontal size +50 at the end of pubs.js.

Ex:

  '&chs=400x200' +                                 // size
to
  '&chs=450x200' +                                 // size

Too many papers in one year
---------------------------

Same thing goes for too many papers. The current height is set for 2009's
number of papers, which is our current max. If a year exceeds that number, a new
height will have to be set in the same way as the length above.

Legacy
------

You'll notice a number of PDFs and HTML pages in this directory up to 2012.
Their example is not to be followed, and used to be how we dealt with papers.
We don't add a page per paper anymore, nor do we store the PDFs in our server.

Update
------

The website should be updated automatically, but could take a while. If after
a day or so it hasn't been updated, please ask on llvm-admin@lists.llvm.org
and someone will do it for you, and hopefully fix the update problem.
