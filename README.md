# Apache Zeppelin

**Documentation:** [User Guide](http://zeppelin.apache.org/docs/latest/index.html)<br/>
**Mailing Lists:** [User and Dev mailing list](http://zeppelin.apache.org/community.html)<br/>
**Continuous Integration:** [![Build Status](https://travis-ci.org/apache/zeppelin.svg?branch=master)](https://travis-ci.org/apache/zeppelin) <br/>
**Contributing:** [Contribution Guide](https://zeppelin.apache.org/contribution/contributions.html)<br/>
**Issue Tracker:** [Jira](https://issues.apache.org/jira/browse/ZEPPELIN)<br/>
**License:** [Apache 2.0](https://github.com/apache/zeppelin/blob/master/LICENSE)


**Zeppelin**, a web-based notebook that enables interactive data analytics. You can make beautiful data-driven, interactive and collaborative documents with SQL, Scala and more.

Core feature:
   * Web based notebook style editor.
   * Built-in Apache Spark support


To know more about Zeppelin, visit our web site [http://zeppelin.apache.org](http://zeppelin.apache.org)


## Getting Started

### Install binary package
Please go to [install](http://zeppelin.apache.org/docs/snapshot/install/install.html) to install Apache Zeppelin from binary package.

### Build from source
Please check [Build from source](http://zeppelin.apache.org/docs/snapshot/install/build.html) to build Zeppelin from source.


### Customizations
1. Enhancement of Cassandra interpreter to call SOLR api if appropriate input is provided.
2. Ability to to faceted search with doc.date "range" functions and tabular formatting for compatible display.
3. Enhancement of Shell interpreter to integrate with ActiveMQ for specific 'hardcoded' queue reading. This feature is used to pull data every 1 second through a rest api trigger for zeppelin notebooks.
