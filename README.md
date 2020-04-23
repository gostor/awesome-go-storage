# Awesome Go Storage [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Go storage projects and libraries. Inspired by [awesome-go](https://github.com/avelino/awesome-go).


### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/gostor/awesome-go-storage/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/gostor/awesome-go-storage/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*


### Contents

- [Awesome Go Storage](#awesome-go-storage)
    - [Storage Server](#storage-server)
    - [Key-Value Store](#key-value-store)
    - [File System](#file-system)
    - [Database](#database)
    - [Database Drivers](#database-drivers)


## Storage Server

*Storage Servers implemented in Go.*

* [minio](https://github.com/minio/minio) - Minio is an open source object storage server compatible with Amazon S3 APIs.
* [rclone](https://github.com/ncw/rclone) - "rsync for cloud storage" - Google Drive, Amazon Drive, S3, Dropbox, Backblaze B2, One Drive, Swift, Hubic, Cloudfile…
* [perkeep](https://github.com/perkeep/perkeep) - Perkeep is your personal storage system for life: a way of storing, syncing, sharing, modelling and backing up content.
* [s3git](https://github.com/s3git/s3git) - Git for Cloud Storage. Distributed Version Control for Data.
* [storj](https://github.com/storj/storj) - Decentralized cloud object storage that is affordable, easy to use, private, and secure. 
* [rook](https://github.com/rook/rook) - Open, Cloud Native, and Universal Distributed Storage.
* [longhorn](https://github.com/rancher/longhorn) Longhorn is an open source persistent block storage server delivered via containers. 

## Key-Value Store

*Key-Value Store implemented in Go.*

* [Bitcask](https://github.com/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).
* [Bitraft](https://github.com/prologic/bitraft) -- Bitraft is a distributed raft-based key/value store with a Redis-compatible protocol. It uses [Bitcask](https://github.com/prologic/bitcask) for high performance/throughout and low latency.
* [BadgerDB](https://github.com/dgraph-io/badger) - BadgerDB is an embeddable, persistent, simple and fast key-value (KV) database written in pure Go. It's meant to be a performant alternative to non-Go-based key-value stores like RocksDB.
* [biscuit](https://github.com/dcoker/biscuit) - Biscuit is a multi-region HA key-value store for your AWS infrastructure secrets.
* [consul](https://github.com/hashicorp/consul) - Distributed consistent replicated key-value store for service discovery and configuration.
* [diskv](https://github.com/peterbourgon/diskv) - A disk-backed key-value store.
* [etcd](https://github.com/coreos/etcd) - Distributed reliable key-value store for the most critical data of a distributed system.
* [go-cache](https://github.com/patrickmn/go-cache) - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.

## File System

*File Systems implemented in Go.*

* [afero](https://github.com/spf13/afero) - A FileSystem Abstraction System for Go
* [fsnotify](https://github.com/fsnotify/fsnotify) - Cross-platform file system notifications for Go.
* [gcsfuse](https://github.com/GoogleCloudPlatform/gcsfuse) - A user-space file system for interacting with Google Cloud Storage.
* [git-lfs](https://github.com/git-lfs/git-lfs) - Git extension for versioning large files.
* [go-systemd](https://github.com/coreos/go-systemd) - Go bindings to systemd socket activation, journal, D-Bus, and unit files.
* [goofys](https://github.com/kahing/goofys) - A high-performance, POSIX-ish Amazon S3 file system written in Go.
* [minikeyvalue](https://github.com/geohot/minikeyvalue) - A ~1000 line distributed key value store.
* [seaweedfs](https://github.com/chrislusf/seaweedfs) - SeaweedFS is a simple and highly scalable distributed file system for small files.
* [svfs](https://github.com/ovh/svfs) - A virtual file system over Openstack Swift built upon fuse.


## Database

*Databases implemented in Go.*

* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
* [bolt](https://github.com/boltdb/bolt) - A low-level key/value database for Go. This original version by Ben Johnson has been marked as unmaintained and forked by [CoreOS bbolt](https://github.com/coreos/bbolt).
* [buntdb](https://github.com/tidwall/buntdb) - A fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* [cache2go](https://github.com/muesli/cache2go) - An in-memory key:value cache which supports automatic invalidation based on timeouts.
* [cockroach](https://github.com/cockroachdb/cockroach) - A Scalable, Geo-Replicated, Transactional Datastore
* [couchcache](https://github.com/codingsince1985/couchcache) - A RESTful caching micro-service backed by Couchbase server.
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - A SQL Database with Blockchain features.
* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [diskv](https://github.com/peterbourgon/diskv) - A home-grown disk-backed key-value store.
* [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* [emitter](https://github.com/emitter-io/emitter) - Scalable, low-latency, distributed & secure pub/sub database with time-series message storage, suitable for IoT, gaming, apps and real-time web.
* [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
* [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
* [geocache](https://github.com/melihmucuk/geocache) - An in-memory cache that is suitable for geolocation based applications.
* [go-cache](https://github.com/pmylund/go-cache) - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [goleveldb](https://github.com/syndtr/goleveldb) - An implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in the Go.
* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
* [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
* [noms](https://github.com/attic-labs/noms) - The versioned, forkable, syncable database.
* [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.
* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database.
* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
* [scribble](https://github.com/nanobox-io/golang-scribble) - A tiny flat file JSON store.
* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
* [Tile38](https://github.com/tidwall/tile38) - A geolocation DB with spatial index and realtime geofencing.

*Database schema migration.*

* [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go
* [goose](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
* [migrate](https://github.com/golang-migrate/migrate) - Database migration handling in Golang support MySQL, PostgreSQL, Cassandra, and SQLite.
* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to support soon for Postgres, SQLite, MongoDB, etc.,
* [soda](https://github.com/markbates/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.

*Database tools.*

* [go-mysql](https://github.com/siddontang/go-mysql) - A go toolset to handle MySQL protocol and replication.
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Support statement and row based replication.
* [orchestrator](https://github.com/outbrain/orchestrator) - MySQL replication topology manager & visualizer
* [pgweb](https://github.com/sosedoff/pgweb) - A web-based PostgreSQL database browser
* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.
* [usql](https://github.com/xo/usql) - universal command-line interface for SQL databases

*SQL query builder, libraries for building and using SQL.*

* [buildsqlx](https://github.com/arthurkushman/buildsqlx) - Go Database query builder library
* [dat](https://github.com/mgutz/dat) - Go Postgres Data Access Toolkit
* [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use it with ease.
* [goqu](https://github.com/doug-martin/goqu) - An idiomatic SQL builder and query library.
* [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
* [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs.
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - a tool to generate a Go ORM tailored to your database schema. It is a "database-first" ORM as opposed to "code-first", and you must first create your database.
* [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.


## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go
    * [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that using database/sql.
    * [go-bqstreamer](https://github.com/rounds/go-bqstreamer) - BigQuery fast and concurrent stream insert.
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver in go language.
    * [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that using database/sql.
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that using database/sql.
    * [gofreetds](https://github.com/minus5/gofreetds) Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
    * [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
    * [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
    * [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
    * [cayley](https://github.com/google/cayley) - A graph database with support for multiple backends.
    * [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
    * [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go
    * [go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go
    * [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK
    * [gocql](http://gocql.github.io) - A Go language driver for Apache Cassandra.
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
    * [gorethink](https://github.com/GoRethink/gorethink) - Go language driver for RethinkDB
    * [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV   
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - The Go driver for MongoDB
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.
    * [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang
    * [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
    * [redis](https://github.com/go-redis/redis) - Redis client for Golang
    * [redis](https://github.com/hoisie/redis) - A simple, powerful Redis client for Go.
    * [redis](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.

* Search and Analytic Databases
    * [bleve](https://github.com/blevesearch/bleve) - A modern text indexing library for go.
    * [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.
    * [elastigo](https://github.com/mattbaird/elastigo) - A Elasticsearch client library.
    * [goes](https://github.com/belogik/goes) - A library to interact with Elasticsearch.
    * [skizze](https://github.com/seiflotfy/skizze) - A probabilistic data-structures service and storage.

* Multiple Backends
    * [gokv](https://github.com/philippgille/gokv) - A simple key-value store interface and many implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more)
