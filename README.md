This will be a README. That will be nice.

GitHub pages
-------------

Web stuff appears at:
http://edthedev.github.io/savannahgreenurbana

Custom Domain will be:
	savannah-green.org

TODO:
https://help.github.com/articles/tips-for-configuring-an-a-record-with-your-dns-provider/

With your DNS provider, create A records that resolve to the following IP addresses::

    192.30.252.153
	192.30.252.154

Then confirm via dig::

	dig example.com +nostats +nocomments +nocmd
	;example.com
	example.com.   73  IN  A 192.30.252.153
	example.com.   73  IN  A 192.30.252.154

Jekyll
-------

More on Jekyll:
https://www.andrewmunsell.com/tutorials/jekyll-by-example/tutorial

To serve the local copy::

	jekyll serve

Then visit http://0.0.0.0:4000/

Soon, hoa.edthedev.com should also work...
	- Using an A record, since it will ultimately be an apex domain.

