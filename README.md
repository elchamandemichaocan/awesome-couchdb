<p>
  <br>
  <img width="300" src="https://rawgit.com/quangv/awesome-couchdb/master/logo--couch.png" alt="awesome couchdb logo">
  <br>
</p>

# Awesome CouchDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated meta resources & best practices list for CouchDB.

**[CouchDB](http://couchdb.apache.org/)** is a document-oriented NoSQL database that syncs.

Pull-Requests are welcomed.

## Patterns & Best Practices

- [CouchDB Best Practices](http://ehealthafrica.github.io/couchdb-best-practices/) - CouchDB Best Practices, eHealth Africa
- [Pagination strategies with PouchDB ](https://pouchdb.com/2014/04/14/pagination-strategies-with-pouchdb.html)
- [12 pro tips for better code with PouchDB](https://pouchdb.com/2014/06/17/12-pro-tips-for-better-code-with-pouchdb.html)


### Map/Reduce

- [PouchDB - Secondary Indexes](https://pouchdb.com/2014/05/01/secondary-indexes-have-landed-in-pouchdb.html)
- [Cloudant - MapReduce Primer](https://cloudant.com/blog/mapreduce-from-the-basics-to-the-actually-useful/#.WIDBfRsrKUl) - great intro on reduce, group, group_level
- [CouchDB - Using View Collation](http://docs.couchdb.org/en/2.0.0/couchapp/views/joins.html#using-view-collation)
- [CouchDB - Views Collation](http://docs.couchdb.org/en/2.0.0/couchapp/views/collation.html)
- [Cloudant - MapReduce and the Secondary Index](https://developer.ibm.com/clouddataservices/docs/cloudant/get-started/mapreduce-and-the-secondary-index/) - (video)
- [Cloudant - Design Documents](https://docs.cloudant.com/design_documents.html)
- [Cloudant - Design Document Management](https://docs.cloudant.com/design_document_management.html) - how to manage design doc changes in production


### Joins

- [Joins with Views](http://docs.couchdb.org/en/2.0.0/couchapp/views/joins.html#joins-with-views)
- [Grouping related documents together in Cloudant](https://docs.cloudant.com/transactions.html) - an approach that leverages CouchDB high availability nature.


### Document Versioning

- [Document Revisions](https://wiki.apache.org/couchdb/Document_revisions?action=show&redirect=DocumentRevisions) - from wiki
- [Simple Document Versioning with CouchDB](http://web.archive.org/web/20100701165612/http://blog.couch.io/post/632718824/simple-document-versioning-with-couchdb)


## Blogs

- [Official CouchDB Blog](https://blog.couchdb.org/)


## Docs

- [Official CouchDB Docs](http://docs.couchdb.org/)
- [FAQ (old wiki)](https://wiki.apache.org/couchdb/Frequently_asked_questions) - seems to have more faqs than the [new wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Frequently+Asked+Questions)

## Books

- [CouchDB - The Definitive Guide](http://guide.couchdb.org/)
- [List of books on the CouchDB Wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Books)


## Videos

- [10 Common Misconceptions about CouchDB ](https://www.youtube.com/watch?v=BKQ9kXKoHS810) - more videos from this [conference](http://conf.couchdb.org/)
- [The NoSQL Tapes](http://nosqltapes.com) - CouchDB is discussed on [Volume 5 - CouchDB](http://nosqltapes.com/video/hoffman-and-kocoloski-on-cloudant-and-couchdb), [Volume 8 - MapReduce](http://nosqltapes.com/video/understanding-mapreduce-with-mike-miller)
- [Scaling Out CouchDB with BigCouch](http://www.oreilly.com/pub/e/1760)
- [IBM - The New Builders Webinar Series](https://event.on24.com/eventRegistration/EventLobbyServlet?target=reg20.jsp&partnerref=cdc&eventid=1240121&sessionid=1&key=9E23B44802902EAD0BB2603F0434742E&regTag=35370&sourcepage=register)


## Community

- [IRC](http://webchat.freenode.net/?channels=couchdb) - `irc://irc.freenode.net/couchdb`
- [Apache CouchDB Conf](http://conf.couchdb.org/) - (lots of video links)
- [CouchDB Bylaws](http://couchdb.apache.org/bylaws.html), [Minutes](https://whimsy.apache.org/board/minutes/CouchDB.html)


### Mailing List

> -dev is where developers of couchdb chat, -user is where users of couchdb chat
> and there's some crosstalk ofc
> -dev is appropriate if you're talking about changes to couchdb itself ("developer" doesn't mean you have to have a commit bit or anything) -rnewson

- [Mailing Lists](https://mail-archives.apache.org/mod_mbox/#couchdb) - [(descriptions)](http://svn.apache.org/repos/asf/couchdb/site/htdocs/community/lists.html?p=900000)
- [grokbase](http://grokbase.com/s/couchdb) - Mailing lists in a [StackOverflow](http://stackoverflow.com/questions/tagged/couchdb)-like interface


[:star2:**The** ***Amazing*** **CouchDB Committers** *and* **Project Managers** :heart_eyes_cat:](http://people.apache.org/committers-by-project.html#couchdb) 


### Companies

- [Cloudant](https://cloudant.com/) - distributed database as a service (DBaaS)
- [Couchbase](https://www.couchbase.com/) - NoSQL Database
- [Smileupps](https://www.smileupps.com/) - CouchDB hosting.
- [IrisCouch](http://www.iriscouch.com/) - Cloud CouchDB.
- [eHealth Africa](https://github.com/eHealthAfrica) - eHealth Africa


### Related Projects

- [PouchDB](https://pouchdb.com/) - a pocket-sized database.
- [Hoodie](http://hood.ie/) - a backend for Offline First applications


## Misc/Technical

- [Dynamo and CouchDB Clusters](https://web.archive.org/web/20160311144130/https://cloudant.com/blog/dynamo-and-couchdb-clusters/#.WIEp4xsrKUk)
- [Google’s paper on Sawzall](http://research.google.com/archive/sawzall.html) - Exotic Reductions Examples
- [What Every Developer Should Know About CouchDB](http://www.dimagi.com/blog/what-every-developer-should-know-about-couchdb/)
- [CouchDB Maximum Database Size](http://www.nosql.se/2011/09/couchdb-maximum-database-size/)


### Attachments

- [PouchDB - Attachments are overrated](https://pouchdb.com/2014/06/17/12-pro-tips-for-better-code-with-pouchdb.html) - _"Update: since this post was written, the stability and performance of attachments in PouchDB has greatly improved. ..."_
- [Cloudant - Attachments Performance Considerations](https://docs.cloudant.com/attachments.html#performance-considerations)
- [Are attachments duplicated for each revision?](http://grokbase.com/t/couchdb/user/14a1phbzrb/are-attachments-duplicated-for-each-revision-as-well)


### Backups

- [Simple CouchDB and Cloudant Backup](https://developer.ibm.com/clouddataservices/2016/03/22/simple-couchdb-and-cloudant-backup/)
- [Cloudant Backup Guide](https://docs.cloudant.com/backup-guide.html)


### CouchApps

- [List of CouchApps](https://couchapp.readthedocs.io/en/latest/user/list-of-couchapps.html)
- [Ddoc Lab](http://ddoc.me/) - Create couchapps and CouchDB design docs right in your browser.


### Scaling

- [Bitnami CouchDB](https://bitnami.com/stack/couchdb) - Bitnami makes it easy to run CouchDB in the cloud.


## Resource Lists

- [Official CouchDB Wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Apache+CouchDB+Wiki)
- [Official CouchDB Wiki (old)](https://wiki.apache.org/couchdb/) - (some things aren't on new wiki yet)
- [Cloudant Official Guides](https://docs.cloudant.com/guides.html) - applicable to CouchDB
- [List of CouchDB Clients](https://cwiki.apache.org/confluence/display/COUCHDB/CouchDB+clients)
- [List of CouchDB Useful Utilities](https://cwiki.apache.org/confluence/display/COUCHDB/Useful+utilities)
- [Old Wiki's Related Projects List](https://wiki.apache.org/couchdb/Related_Projects)

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
