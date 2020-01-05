This README is just a quick start document. Content is mainly for windows. You can find more detailed documentation about redis at https://redis.io/.

1.Download and install the Redis database
* Windows https://github.com/ServiceStack/redis-windows
* Linux https://redis.io/

2.Run the redis-server executable file to start the database. The default address is 127.0.0.1 and the port is 6379. You can modify the parameters in redis.windows-service.conf.

3.redis-cli is a built-in Redis console client that can execute redis commands to modify and view various data. You can also download other redis client software for operation.

4.Finally, you only need to enable the SDRedis plugin in the project, create a URedisObject instance and initialize the Redis connection parameters to use various nodes normally.
 
5.You can also check out the SDRedis plugin blueprint, which contains some simple examples.