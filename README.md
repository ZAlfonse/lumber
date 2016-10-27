# Lumber
ANSI Logging module for Go. Each log type has it's own color!!

###Initialize a new logger like so: 

`logger = lumber.NewLogger(lumber.TRACE)`


###6 Levels of logging:
- `lumber.TRACE`
- `lumber.DEBUG`
- `lumber.SUCCESS`
- `lumber.INFO`
- `lumber.WARNING`
- `lumber.ERROR`


###Log by calling:

`logger.Info("Here's the number: ", 1)`

`logger.Warning("Uh oh, this number doesn't look right: ", 3)`

etc..


###Color codes:
| Log Level | Color Code |
|-----------|------------|
| TRACE     | 32m        |
| DEBUG     | 35m        |
| SUCCESS   | 32m        |
| INFO      | 36m        |
| WARNING   | 31m        |
| ERROR     | 31m        |

###Looks like:
![](https://s.alfnz.com/pUOkI.png)
