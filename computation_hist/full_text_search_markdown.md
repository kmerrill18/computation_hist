Most relevant information that I know concerning full text searching
can be found at the following links. Instead of typing all of it out again, I'm
going to put the resources here and then I will at least save you a few minutes in
Googling.

https://en.wikipedia.org/wiki/Full-text_search

^The wikipedia page is a helpful place to start. I would recommend it to start getting your
head around full text search.

https://blogs.loc.gov/thesignal/2014/08/making-scanned-content-accessible-using-full-text-search-and-ocr/

^ This is a blog from the library of Congress about full-text searching scanned documents.
It addresses concerns of incomplete metadata and inability to accurately OCR some old text.
The hyperlinks within the document are also helpful; I would recommend following those.

https://docs.djangoproject.com/en/2.1/ref/contrib/postgres/search/

^This is django documentation for searching.

From my reading it seems to me you will probably use another source like Apache Solr in
conjuction with django for full text search. Here's some resources on that:

http://lucene.apache.org/solr/
http://haystacksearch.org/
https://www.egrovesys.com/blog/solr-implementation-using-django-haystack/

That's about all I have. Best of luck.