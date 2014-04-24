The simplest possbile Solr configuration.

To run, be sure to pass the full path to the `solr` command, e.g.
```
$ solr /path/to/simple-solr/simple-solr-home
$ curl http://localhost:8983/solr/simple-collection/update -H 'Content-type:application/json' -d '[{"simple-field": "simple-value"}]'
```
