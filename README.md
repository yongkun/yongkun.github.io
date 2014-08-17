#yongkun wang at github
=================

##[iombench](http://yongkun.github.io/iombench/) 
A microbenchmark for storage systems or devices such as hard disk and flash SSD. 
[Source](https://github.com/yongkun/iombench)

##[Masterless Ack Flume](http://yongkun.github.io/flume-0.9.3-cdh3u0-rakuten/)
I created a new release v0.10 based on 0.9.3 (cdh3u0), major changes include: 
- Masterless Ack, please check https://issues.apache.org/jira/browse/FLUME-640, which was supposed to be merged into 0.10 if Flume was not upgraded to NG; 
- Append to HDFS with new file rotation method.
https://github.com/yongkun/flume-0.9.3-cdh3u0

##[Trift bi-directional](http://yongkun.github.io/thrift-reuse-conn)
A simple example on how to reuse the thrift connection to transmit data bi-directionally.

##[Thrift buffered](http://yongkun.github.io/thrift/)
I created two release (thrift-0.6.2 and thrift-0.7.1) to fix some issues in early version (0.6.x, 0.7.x) which is used for Apache Flume. These issues have been fixed in later versions (0.8.x+) of original repo. Main change is the buffered input/output stream to improve the performance for on 0.6.x & 0.7.x, change on 0.7.x also includes 'oneway' fix (THRIFT-1447). Two new versions are created: thrift-0.6.2 and thrift-0.7.1.
