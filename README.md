This project has docker-compose file for running [Jaeger] with [scylladb] as a storage database (not casandra).

This project still in its initial stage, we only test by putting tracing inputs from a sample [PHP project] which uses opencensus to send tracing data to Jaeger. 

How to run
==========

```
docker-compose up -d
```

Versions 
========

1. Jaeger: 1.13.1
2. scylladb: 3.0.8

[Jaeger]: https://www.jaegertracing.io/
[scylladb]: https://www.scylladb.com/
[PHP project]: https://github.com/varunpalekar/laravel-opencensus-example