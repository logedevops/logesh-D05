# logesh-D05
task1 linux basic commands
root@DESKTOP-POH0T0A:/home/logesh# mkdir task1
root@DESKTOP-POH0T0A:/home/logesh# cd task1
root@DESKTOP-POH0T0A:/home/logesh/task1# touch at{11..30}.txt
root@DESKTOP-POH0T0A:/home/logesh/task1# ls
at11.txt  at13.txt  at15.txt  at17.txt  at19.txt  at21.txt  at23.txt  at25.txt  at27.txt  at29.txt
at12.txt  at14.txt  at16.txt  at18.txt  at20.txt  at22.txt  at24.txt  at26.txt  at28.txt  at30.txt
root@DESKTOP-POH0T0A:/home/logesh/task1# mv at11.txt at11.yml
root@DESKTOP-POH0T0A:/home/logesh/task1# mv at12.txt at12.yml
root@DESKTOP-POH0T0A:/home/logesh/task1# mv at13.txt at13.yml
root@DESKTOP-POH0T0A:/home/logesh/task1# mv at14.txt at14.yml
root@DESKTOP-POH0T0A:/home/logesh/task1# mv at15.txt at15.yml
root@DESKTOP-POH0T0A:/home/logesh/task1# ls -l
total 0
-rw-r--r-- 1 root root 0 Nov 26 19:04 at11.yml
-rw-r--r-- 1 root root 0 Nov 26 19:04 at12.yml
-rw-r--r-- 1 root root 0 Nov 26 19:04 at13.yml
-rw-r--r-- 1 root root 0 Nov 26 19:04 at14.yml
-rw-r--r-- 1 root root 0 Nov 26 19:04 at15.yml
-rw-r--r-- 1 root root 0 Nov 26 19:04 at16.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at17.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at18.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at19.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at20.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at21.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at22.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at23.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at24.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at25.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at26.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at27.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at28.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at29.txt
-rw-r--r-- 1 root root 0 Nov 26 19:04 at30.txt
root@DESKTOP-POH0T0A:/home/logesh/task1# ls | head-5
head-5: command not found
root@DESKTOP-POH0T0A:/home/logesh/task1# ls | head -5
at11.yml
at12.yml
at13.yml
at14.yml
at15.yml
root@DESKTOP-POH0T0A:/home/logesh/task1#
