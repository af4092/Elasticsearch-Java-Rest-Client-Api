# Elasticsearch-Java-Rest-High-Level-Client-Api
Elasticsearch Java Rest High Level Client Api

- [Elasticsearch Java API Client](https://www.elastic.co/guide/en/elasticsearch/client/java-api-client/current/index.html) - Documentation which provides the Java API client
- [Java Low Level REST Client](https://www.elastic.co/guide/en/elasticsearch/client/java-api-client/current/java-rest-low.html) - The low-level client’s features include:
  - minimal dependencies
  - load balancing across all available nodes
  - failover in case of node failures and upon specific response codes
  - failed connection penalization (whether a failed node is retried depends on how many consecutive times it failed; the more failed attempts the longer the client will wait before trying that same node again)
  - persistent connections
  - trace logging of requests and responses
  - optional automatic discovery of cluster nodes
