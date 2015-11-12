#Map Reduce Unique pages counter (mrupc)

This project is a simple project to try map reduce.

## Input 
The program will recive as input one or more folders. Each one contains log files, in [Common log format](https://en.wikipedia.org/wiki/Common_Log_Format), of web servers accesses.

## Output
The program will leave the result in the directory received as parameter, using the next format:
```
web-page   number-of-unique-acceses
```

Example:
```
/  200
/index.html  24
/news/today.html 100
```
