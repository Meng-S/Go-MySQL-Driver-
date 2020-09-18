#  Go-MySQL-Driver-中文
一个用于Go [database/sql](https://golang.org/pkg/database/sql/) 包的MySQL驱动程序
![Go-MySQL-Driver logo](https://raw.github.com/wiki/go-sql-driver/mysql/gomysql_m.png "Golang Gopher holding the MySQL Dolphin")
---------------------------------------
---------------------------------------
  * [特点](#特点)
  * [Requirements](#requirements)
  * [Installation](#installation)
  * [Usage](#usage)
    * [DSN (Data Source Name)](#dsn-data-source-name)
      * [Password](#password)
      * [Protocol](#protocol)
      * [Address](#address)
      * [Parameters](#parameters)
      * [Examples](#examples)
    * [Connection pool and timeouts](#connection-pool-and-timeouts)
    * [context.Context Support](#contextcontext-support)
    * [ColumnType Support](#columntype-support)
    * [LOAD DATA LOCAL INFILE support](#load-data-local-infile-support)
    * [time.Time support](#timetime-support)
    * [Unicode support](#unicode-support)
  * [Testing / Development](#testing--development)
  * [License](#license)

---------------------------------------
## 特点
* 轻巧[快速]https://github.com/go-sql-driver/sql-benchmark "golang MySQL-Driver performance")
* 纯原生golang实现
* 通过 TCP/IPv4, TCP/IPv6, Unix domain sockets 和 [custom protocols](https://godoc.org/github.com/go-sql-driver/mysql#DialFunc)连接
