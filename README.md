# BashThreadPool

Strictly speaking Bash doesn't support Light-Weight Processes or threads.
Nevertheless it is possible to implement a "thread pool"-like script without using any external tools.
This can be useful if a high level language (i.e. Java, Python, Perl) is not available and the Bash
interpreter is the only tool at hand. The code used in this repo was tested in Bash V3.2.25 and later.

To start the pool:
`bash pool.sh start`

To check the workers statuses:
`bash pool.sh status`

To stop the pool:
`bash pool.sh stop`

[More info](https://www.celersms.com/threadpool-bash.htm)
