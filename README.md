# Command Line MySQL Query Execute

## Connect to MySQL
* You'll need to open `Command Prompt` as Administrator
* Then run the code to connect to database and restore backup file in it.

> **Note :-** Make sure to check `Alter` command before executing it. It only support upto 3 `Alter` at once, any more then that will go in the next `Alter`

```bash
mysql -u {username} -p {password} -h {hostname} -P {port} {database_name} < {file_destination}
```