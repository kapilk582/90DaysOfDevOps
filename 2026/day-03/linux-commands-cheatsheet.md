Process management:-
ps – shows the summary about processes.
ps aux – it shows detailed all executed processes.
du – it checks file and directory and display with their size.
df / df -h : – it shows disk usage and display how much free and how much consuming on particular path.
top / htop – it checks running process with PID and with system uptime, load average, process stages, memory, swap. 
kill / kill -9 :  – we can kill any process using process id with this command. (ex. Kill 983 or kill -9 983).
pstree :-  it shows hierarchy view of processes with parent and child relationship
nice :- this is used to launch a process with a specified priority. Lower values represent higher priority 
(ex- nice -n 10 script.sh).
renice :- This is allow to users to adjust the priority of a running process (Ex:- renice 5 -p 1234).

File management:-
mkdir: for creating a directory or folder. (Ex: mkdir newfolder)
touch: for creating a file. (Ex: touch file.txt)
vi/nano:  it used as a editor for edit or write a file. (Ex: vi file.txt)
cp: this is used for copy  file or folder (Ex: cp -r newfolder   myfolder)
mv: this is used for move and rename file/folder (Ex: mv -r newfolder   myfolder).
rm: used for remove a file or directory.
ln -s: used for creating softlink (if source file deleted then softlink will not work).
ln: used for creating hardlink (if source file deleted but hardlink work proper).
grep: used for pattern matching in a log file or file and produce output.
ls: shows list of content of a directory  (ls -l for detailed info, ls -a shows hidden file also).
pwd: it shows present working directory of user.
cd: it is use for cd the directory.

Netwotk management:-
ping: this command used for checking a particular system or web or service working properly or not .
netstat: it display network statistics and I-Node related info.
ip addr: show ip related information.
