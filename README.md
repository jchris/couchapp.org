# CouchApp.org

This app is the landing page for [the CouchApp community website](http://couchapp.org). It's just a version of [Sofa](http://github.com/jchris/sofa) that links to a few other exciting apps on CouchApp.org.

## Installation

This app expects to be configured with CouchDB's vhosts parammeter, to a rewriter. To set this app up, install it in a database, and then configure CouchDB with a vhost like:

    [vhosts]
    couchapp.com = /couchapp/_design/couchapp.org/_rewrite

You'll need to add the `author` role to anyone you'd like to have writing posts on the blog. See the Sofa documentation for details.