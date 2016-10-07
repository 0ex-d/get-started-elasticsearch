# getting-started-elasticsearch

A getting-started guide to [Elasticsearch](https://www.elastic.co) or ES that would save your sanity when it comes to Large scale distributed search.

To know more about Elastic Search, go [here](http://bin63.com/how-to-install-elasticsearch-on-windows)

## Preamble

In order to run ES, you need a computer system that runs on Windows 32-bit or 64-bit OS and has a CMD or CYGWIN. 
And a browser(preferably Google Chrome). 
And dude, It's not a must to run your app on ElasticSearch (You ain't James bound).


### Windows

In your cmd or cygwin type in the below

```
$ cd C:/(installation folder)/bin/
$ elasticsearch.bat
```

ES server defaults to `http://localhost:9200`. You should see something like this in your browser

```
{
  "name" : "Mop Man",
  "cluster_name" : "elasticsearch",
  "cluster_uuid" : "2uf4rO45yyuotrT-nrxOEw",
  "version" : {
    "number" : "2.4.1",
    "build_hash" : "c67dc32e24162035d18d6fe1e952c4cbcbe79d16",
    "build_timestamp" : "2016-09-27T18:57:55Z",
    "build_snapshot" : false,
    "lucene_version" : "5.5.2"
  },
  "tagline" : "You Know, for Search"
}
```

### Use case with curl

Get started doing something with your curl

```
$ curl -X GET http://localhost:9200/
```
