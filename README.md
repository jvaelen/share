About
--
Share is a python script that, ontop of github pages, helps people with moving from their laptop to their tablet when they want to read an article online.


Usage
--
`./share <url>` adds the url to a local file (db) that is used to generate a html page that contains all the files that have been shared.

`./share clear` clears the cache and thus also the html page. Next time you do a share <url>, the index.html will be updated to contain only the newly shared url.

`./share rebuild` when you delete a couple of urls from your local db file, this command rebuilds index.html and pushes it to the server, for fine grained control.

Whenever you execute share with a URL, a commit is automatically issued. This way the github page is instantly updated.
