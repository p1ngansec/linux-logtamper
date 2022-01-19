# linux-logtamper
copy from xi4oyu<br>
modify by zhangwei<br>
you can use "-u number" to delete the number of \`last\`'s user login log.<br>
<br>
<br>
logtamper [-f utmp_filename] -h username hostname		hide username connected from hostname<br>
logtamper [-f wtmp_filename] -w username hostname		erase username from hostname in wtmp file<br>
logtamper [-f lastlog_filename] -m username hostname ttyname YYYY[:MM[:DD[:hh[:mm[:ss]]]]]  modify lastlog info<br>
logtamper [-f wtmp_filename] -u [the number you want to delete in \`last\`, default is 1]<br>
