# docker-apache-pig
Docker container for Apache Pig


# Hadoop & Pig
Apache Pig and Hadoop setup.  Perfect for trying some Pig commands (Pig 0.14.0 with hadoop 2.5.2).

Based on [ipedrazas/hadoop-pig](https://hub.docker.com/r/ipedrazas/hadoop-pig/), fixes ```PATH``` and history server issues.

# Pull the image
```
docker pull hakanserce/apache-pig
```

# Start a container
In order to use the Docker image use:

```
docker run -i -t hakanserce/apache-pig /etc/bootstrap.sh -bash
```

# Test Pig

Once the container has started, execute

```
pig
```

#### Pig Tutorial

If you need a short and easy to follow tutorial to start learning Pig, take a look at [Apache Pig Tutorial by Rohit Menon](http://www.rohitmenon.com/index.php/apache-pig-tutorial-part-1/). 


