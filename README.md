# Shredder

Personal knowledge management through a search bar. Powered by Apache Solr.

Shred all your paper notes and start searching! :tada:



## Steps

1. start solr;
  `bin/solr stop -all`
  `bin/solr start`
1. indexing docs: POST to colletion;
  `bin/post -c <collectionName> <docs|dirs>`
1. search!
1. remember to stop solr;
  `bin/solr stop -all`



## Cores

Potential collections (toggle-able before search):

- notes (manually written articles),
- logs (sparks, rambles, and mind farts),
- literature (other's work),



## TODO

- [x] Acknowledge Carrot2 and add its open source license. (Licenses of extensions are included under licenses/ in Solr distribution, e..g licenses/carrot2-mini-LICENSE-BSD_LIKE.txt.)
