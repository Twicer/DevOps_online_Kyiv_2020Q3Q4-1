![alt text](/m5/task5.3/Linux3.1.PNG) <br />
![alt text](/m5/task5.3/Linux3.2.PNG) <br />
`cd` <br />
Change directory to home dir. <br />

`mkdir test` <br />
create new directory `test`. <br />

`cd test` <br />
change dir to `test`. <br />

`touch test1.txt` <br />
create new file `test1.txt`. <br />

`echo “test1.txt” > test1.txt`<br />
write _test1.txt_ text into `test1.txt`. <br />

`ls -l` <br />
check content of current direcctory. <br />

`ln test1.txt test2.txt`<br />
create hard link from `test1.txt` to `test2.txt`. <br />

`ls -l`<br />
check content of current direcctory (here we can see how the hard link displayed). <br />

`echo “test2.txt” > test2.txt`<br />
write some text in `test2.txt`. <br />

`cat test1.txt test2.txt` <br />
check the content both of `test1.txt` and `test2.txt`. <br />

`rm test1.txt` <br />
remove `test1.txt` file. <br />

`ls -l` <br />
check what we have now in our current dir. <br />

`ln -s test2.txt test3.txt`<br />
create soft link from `test2.txt` to `test3.txt`. <br />

`ls -l` <br />
check content of current direcctory (here we can see how the soft link displayed). <br />

`rm test2.txt; ls -l` <br />
executting two commands in one line like removing `test2.txt` and checking content of current dir. <br />

![alt text](/m5/task5.3/Linux3.3.PNG) <br />
![alt text](/m5/task5.3/Linux3.4.PNG) <br />

`mount` <br />
check mounted devices<br />

`blkid`<br />
determine the type of the content (in the screen we can see type of each block device).<br />

`mount | grep sda` <br />
get information about mounted devices that contains _sda_.<br />

`dmesg | grep sda`<br />
check messages from kernel ring buffer that contains _sda_.<br />

`sudogrep -R -e “root” /etc > root_entries.txt`<br />
searching information whitch contains _root_ pattern in _/etc_ diectory and writing output in `root_entries.txt` file. <br />

![alt text](/m5/task5.3/Linux3.5.PNG) <br />
![alt text](/m5/task5.3/Linux3.6.PNG) <br />
![alt text](/m5/task5.3/Linux3.7.PNG) <br />
![alt text](/m5/task5.3/Linux3.8.PNG) <br />
