# alpine-curator_cli
curator_cli ElasticSearch client Alpine Docker


An Alpine Docker container for [curator_cli](https://www.elastic.co/guide/en/elasticsearch/client/curator/current/singleton-cli.html) ElasticSearch Python client.

Fixes a [bug](https://github.com/elastic/curator/issues/1309) in pip Click.

Tries to be small & simple. For use in pipelines, cronjobs or even manually (ENTRYPOINT is /usr/bin/curator_cli).
