# NewtonCMS - a lightweight CMS for mostly static content

This is not a sophisticated comtent management system, but it is sufficient in scale for many websites.  It is very easy to deploy and modify as needed.  

## Installation

Copy the files "doc" and "tmpl.html" into the document root of the website and set the permissions to allow the webserver to read and execute the files as required.  
The "htaccess" file is provided file as an example of how to configure the Apache web server to execute the "doc" script as a CGI.

Copy the directory "docs" and all contents into the document root.  This directory will eventually contain all the static web pages for the site.  
Web page files under this directory should end in the ".md" extension (for "Markdown" format).

Use a web browser to visit the test page http://domain.com/doc/test . 
This corresponds to the markdown source file "test.md" in the "docs" directory.

