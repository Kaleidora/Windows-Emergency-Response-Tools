# Win Emergency Response Detection Tool



![1](https://github.com/yuag/Select-YARA-Rule-Folder/assets/34123873/c22e11aa-f7ba-4059-a33e-5c930cfb33e9)




<br>
<br>

# Features

System Process List

System Services

System Logs

Network Connections

Scheduled Tasks

Shared Resources

Files Modified in the Last Three Days

Display Process and Service Information

Display Processes and Owners

Yara Scripts (Supports detection of shell, ransomware, mining, etc.)


Yara Script Collection:

https://github.com/InQuest/awesome-yara/tree/master

https://segmentfault.com/q/1010000043271331




<br>
<br>

# Attention

Common Pitfalls When Installing the Yara Library 

libyara.dll No results found

Solution: Perform a global search for libyara.dll

Simply copy the libyara.dll file here to the correct directory (Python 3 root directory).

For reference：https://blog.csdn.net/weixin_43781139/article/details/131087788








<br>
<br>
<br>
<br>
<br>
<br>


# Linux Emergency Response Detection Tool

<img width="704" alt="image" src="https://github.com/yuag/Emergency-response-tools/assets/34123873/ae16d38e-de93-4eab-94dd-6077d9646c3b">


<br>
<br>

<img width="870" alt="image" src="https://github.com/yuag/Emergency-response-tools/assets/34123873/12e01fa8-cc3f-4ae8-9aad-7210671158e8">






<br>
<br>

# Features

1.  Retrieve external network connection status
2.  Display processes
3.  Task startup entries
4.  Check abnormal ports
5.  Check scheduled tasks
6.  Monitor processes communicating with target IPs
7.  Sort CPU usage in descending order
8.  Query historical commands
9.  Files modified within the last 7 days
10. Login records
11. Number of IPs brute-forcing root accounts on the host
12. Identifying IPs involved in brute-force attacks
13. Determining the brute-force username dictionary
14. Successful login dates, usernames, and IPs
15. Query sudo-privileged accounts
16.  Detect files using YARA rules
17.  Execute all commands and export results with one click
18.  Find files added within the last 72 hours            
19.  Exit





<br>
<br>


# Encountered error


ubuntu


Installing Yara error
OSError: /usr/lib/libyara.so: cannot open shared object file: No such file or directory

Simply copy the libyara.so file to this directory.
/usr/lib/libyara.so

root User Permissions
cp -r libyara.so /usr/lib/

<br>
<br>




<br>
<br>

cenetos

cenetos7 Direct installation of Yara fails; it only succeeds in a virtual environment. Subsequent tests will not produce errors.

Using a virtual environment (optional):

If you haven't already set up a virtual environment, consider creating one to isolate the Python environment for this project:


python3 -m venv myenv
source myenv/bin/activate





<br>
<br>
Note: Select a command
16. Use YARA rules to scan files

Do not add single/double quotes to the path, otherwise it will cause an error.

