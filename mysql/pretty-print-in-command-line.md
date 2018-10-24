# Pretty Print in Command Line
When running mysql on the command line, the following select statement provides mangled output, which can be very hard to read.

```sql
mysql> select * from content;
```

If you want to output your statement into a nicely-formatted ASCII table, append `\G` to the end of your statement (but before the semicolon), like so:

```sql
mysql> select * from content\G;
```