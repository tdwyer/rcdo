rcdo - OpenBSD Service Management Program
-----------------------------------------


`rcdo` is a /etc/rc.d service management program written in AWK and no more complicated the what is absolutely necessary.


Features
========

- Edit /etc/rc.d files
- Start, Stop, Restart, and all other actions defined in it's rc.d file


Examples
========


Edit the read-only rc.d service file


    rcdo tor edit


Starting, Stopping, and other actions


    rcdo tor start
    rcdo tor stop
    rcdo tor restart
    rcdo tor *


