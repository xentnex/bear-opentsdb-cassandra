# bear-opentsdb-cassandra

An optimized OpenTSDB for Cassandra 3.x.

***** Cassandra 3.x *****
# Start Cassandra
docker run -td -v /media/miwgates/Depo/Projeler_Docker/bin/Cassandra_3.10/config:/CassandraConfig -e CONFIG_FILE_PATH=/CassandraConfig -e CASSANDRA_CONFIG_FILE_PATH=/CassandraConfig/cassandra.yaml --name Cassandra01 bear/cassandra-3.10:base
