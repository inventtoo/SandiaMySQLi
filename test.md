# Welcome to the Cheesecake MySQLi Database Wrapper 

## What is this?
*Cheesecake* is MySQL Databases wrapper written in PHP to make simple some of the more recurrent tasks in databases management.

*Cheesecake MySQLi Wrapper* is maintained by Marco Fernandez member of the team [inventtoo.com](http://inventtoo.com), please feel free to visit us and send your comments to us.

This project have a MIT License, so you can modify it, redistribute it, print it, burn it, or whatever you want.

## What make Cheesecake MySQL Wrapper better?
It's just lighter and smaller than the most libraries. And, who the hell don't love the cheesecakes?

# Configuration

## How to setup and connect *Cheesecake MySQLi Wrapper*

```php
<?php
require_once 'class_cheesecake.php';
$db = new cheesecake();
$db->open("localhost","user","password","database");
```
## Functions Catalog

|Fn      |Function Name|Inputs                                               |
| ---    | ---         |---                                                  |
|Database|open         |($host, $user, $pswd, $db, $port='', $charset='utf8')|
|Database|close        |                                                     |
|Static  |callStatic   |                                                     |


### Getters / Setters
- get_cmd_connection
- get_last_error_id
- get_last_error
- get_last_query
- get_query_count
- get_time_execution
- get_time_connection
- get_time_last_query
- get_affected_rows
- get_last_id
- get_log
- get_last_log
- set_log
### Commit / Roll-back / Rewind / Free
-transaction_begin
-transaction_commit
-transaction_rollback
-rewind
-free