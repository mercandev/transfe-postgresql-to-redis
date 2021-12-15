#Transfer from Postgresql to Redis

This application, which supports the project we started with the [Url Filter Management API](https://github.com/mercandev/minimal-api-url-filter-management) , saves the data to PostgreSql at regular intervals using Hangfire so that the data on Redis is not lost.

With the project, which is one of the intermediate steps for the amateur ISP network we want to create, the replication process will continue in the face of any problem that may occur in the Redis machine.

