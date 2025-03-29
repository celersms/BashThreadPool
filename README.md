# Thread Pool in Bash

Strictly speaking Bash doesn't support Light-Weight Processes or threads.
Nevertheless it is possible to implement a "thread pool"-like script without using any external tools.
This can be useful if a high level language (i.e. Java, Python, Perl) is not available and the Bash
interpreter is the only tool at hand. The code used in this repo was tested in Bash V3.2.25 and later.

<img src='https://www.celersms.com/images/thpool.png'>

Start the pool:  
`bash pool.sh start`

Check the workers statuses:  
`bash pool.sh status`

Stop the pool:  
`bash pool.sh stop`

[More information](https://www.celersms.com/threadpool-bash.htm)
