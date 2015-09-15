+++
date = "2015-03-19T14:27:51-04:00"
title = "Management"
[menu.main]
  parent = "Sync Reference"
  identifier = "Sync Management"
  weight = 90
  pre = "<i class='fa'></i>"
+++

## Management

The driver provides two mechanisms for examining its state:

- [Logging]({{< relref "driver/reference/management/logging.md" >}}): Comprehensive logging of all operations using [SLF4J](http://www.slf4j.org/)
- [Application Performance Monitoring]({{< relref "driver/reference/management/apm.md" >}}): The Application Performance Monitoring API is an API developers to tap into the commands issues to MongoDB to record performance metrics and/or inspect the commands sent to MongoDB.