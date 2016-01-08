# README #

A "getting started" project for CIS 322, software engineering 1 at University of Oregon.

Pageserver should serve web pages (text files with names that end with .html) and style sheets (text files that end with .css) from the directory in which the server is run.  It should reject URLs that contain '~' or '..' or '//', so that it cannot be used to read files outside of that directory.  For any rejected URL, as well as for URLs that do not match a file in the current directory, your pageserver should respond with 'I don't handle this request', followed by the request.