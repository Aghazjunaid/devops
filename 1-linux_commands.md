Here are some commonly used Linux commands with examples:
1. **ls**: List files and directories in the current directory.
   - `ls`: List files and directories in the current directory.
   - `ls -l`: List files and directories in long format (detailed information).
   - `ls -a`: List all files and directories, including hidden ones.
   - `ls -lh`: List files and directories in long format with human-readable file sizes.

2. **cd**: Change directory.
   - `cd directory`: Change to the specified directory.
   - `cd ..`: Change to the parent directory.
   - `cd ~`: Change to the home directory.
   - `cd -`: Change to the previous directory.

3. **pwd**: Print working directory (displays the current directory).

4. **mkdir**: Create a new directory.
   - `mkdir directory`: Create a new directory with the specified name.
   - `mkdir -p parent/child`: Create nested directories if they don't exist.

5. **rm**: Remove files and directories.
   - `rm file`: Remove the specified file.
   - `rm -r directory`: Remove the specified directory and its contents recursively.
   - `rm -f file`: Forcefully remove the specified file without prompting.
   - `rm -rf directory`: Forcefully remove the specified directory and its contents recursively without prompting.

6. **cp**: Copy files and directories.
   - `cp file destination`: Copy the file to the specified destination.
   - `cp -r directory destination`: Copy the directory and its contents recursively to the specified destination.
   - `cp file1 file2 destination`: Copy multiple files to the specified destination.

7. **mv**: Move or rename files and directories.
   - `mv file destination`: Move the file to the specified destination.
   - `mv file newname`: Rename the file.
   - `mv directory destination`: Move the directory to the specified destination.

8. **cat**: Concatenate and display file content.
   - `cat file`: Display the content of the file.
   - `cat file1 file2`: Concatenate and display the content of multiple files.

9. **grep**: Search for a pattern in files.
   - `grep pattern file`: Search for the specified pattern in the file.
   - `grep -r pattern directory`: Search for the pattern recursively in files within the specified directory.

10. **chmod**: Change file permissions.
    - `chmod permissions file`: Change the permissions of the file.
    - `chmod +x file`: Add execute permission to the file.
    - `chmod -R permissions directory`: Change the permissions recursively for all files and directories within the specified directory.
Certainly! Here are a few more commonly used Linux commands with examples:

11. **touch**: Create an empty file or update the timestamp of an existing file.
    - `touch file`: Create an empty file with the specified name.
    - `touch -a file`: Update the access timestamp of the file.
    - `touch -m file`: Update the modification timestamp of the file.

12. **head**: Display the beginning of a file.
    - `head file`: Display the first 10 lines of the file.
    - `head -n N file`: Display the first N lines of the file.

13. **tail**: Display the end of a file.
    - `tail file`: Display the last 10 lines of the file.
    - `tail -n N file`: Display the last N lines of the file.

14. **wc**: Count lines, words, and characters in a file.
    - `wc file`: Display the number of lines, words, and characters in the file.
    - `wc -l file`: Display only the number of lines in the file.

15. **find**: Search for files and directories.
    - `find directory -name filename`: Search for files or directories with the specified name inside the given directory.
    - `find directory -type f`: Search for files only within the given directory.
    - `find directory -type d`: Search for directories only within the given directory.
    - `find / -name "*.txt"`: Search for all files ending with ".txt" starting from the root directory ("/").

16. **ssh**: Connect to a remote server using SSH (Secure Shell).
    - `ssh username@hostname`: Connect to the remote server with the specified username and hostname.
    - `ssh -p port username@hostname`: Connect to the remote server using a specific port.

17. **wget**: Download files from the web.
    - `wget URL`: Download the file from the specified URL.
    - `wget -c URL`: Resume a partially downloaded file.
    - `wget -r URL`: Download an entire website recursively.

18. **df**: Display disk space usage.
    - `df`: Display disk space usage of all mounted filesystems.
    - `df -h`: Display disk space usage in human-readable format.

19. **free**: Display memory usage.
    - `free`: Display memory usage and available memory.
    - `free -h`: Display memory usage in human-readable format.

20. **history**: View command history.
    - `history`: Display the list of previously executed commands.
    - `history N`: Display the last N commands from the history.

21. **tar**: Create or extract compressed archives.
    - `tar -cvf archive.tar file1 file2`: Create a tar archive file with the specified files.
    - `tar -xvf archive.tar`: Extract the contents of a tar archive.

22. **gzip**: Compress files.
    - `gzip file`: Compress the file and rename it with a .gz extension.
    - `gzip -d file.gz`: Decompress the file.

23. **ping**: Check the network connectivity to a host.
    - `ping hostname`: Send ICMP echo requests to the specified hostname to check network connectivity.
    - `ping -c count hostname`: Send a specific number of echo requests and stop.

24. **ifconfig/ip**: View and configure network interfaces.
    - `ifconfig`: Display network interface configuration (legacy command).
    - `ip addr show`: Display IP addresses and network interface information (modern command).
    - `ip link set interface up/down`: Bring a network interface up or down.

25. **scp**: Securely copy files between local and remote systems.
    - `scp file username@hostname:destination`: Copy the file to the remote system.
    - `scp username@hostname:file destination`: Copy the file from the remote system to the local system.

26. **chown**: Change file/directory ownership.
    - `chown owner file`: Change the owner of the file.
    - `chown owner:group file`: Change the owner and group of the file.

27. **chgrp**: Change group ownership of a file/directory.
    - `chgrp group file`: Change the group of the file.

28. **ln**: Create links between files.
    - `ln -s target linkname`: Create a symbolic link to the target file or directory.

29. **dd**: Convert and copy files.
    - `dd if=input_file of=output_file`: Copy the input file to the output file.
    - `dd if=/dev/zero of=file bs=1M count=100`: Create a file filled with zeros.

30. **uname**: Display system information.
    - `uname`: Display the system's kernel name.
    - `uname -a`: Display detailed system information.

31. **du**: Estimate file and directory disk usage.
    - `du file`: Display the disk usage of the file.
    - `du -h directory`: Display the disk usage of the directory in human-readable format.
    - `du -sh directory`: Display the total disk usage of the directory in human-readable format.

32. **find**: Search for files and directories based on various criteria.
    - `find directory -name filename`: Search for files or directories with the specified name inside the given directory.
    - `find directory -type f`: Search for files only within the given directory.
    - `find directory -type d`: Search for directories only within the given directory.
    - `find / -size +1G`: Search for files larger than 1GB starting from the root directory ("/").

33. **grep**: Search for text patterns in files.
    - `grep pattern file`: Search for the specified pattern in the file.
    - `grep -r pattern directory`: Search for the pattern recursively in files within the specified directory.
    - `grep -i pattern file`: Search for the pattern in a case-insensitive manner.
    - `grep -v pattern file`: Display lines that do not match the pattern.

34. **sed**: Stream editor for text manipulation.
    - `sed 's/old/new/' file`: Replace the first occurrence of "old" with "new" in each line of the file.
    - `sed 's/old/new/g' file`: Replace all occurrences of "old" with "new" in each line of the file.
    - `sed '/pattern/d' file`: Delete lines that match the pattern in the file.

35. **awk**: Text processing and manipulation tool.
    - `awk '{ print $1 }' file`: Print the first field of each line in the file.
    - `awk '/pattern/ { print $2 }' file`: Print the second field of lines that match the pattern in the file.

36. **ps**: Display information about active processes.
    - `ps`: Display information about processes owned by the current user.
    - `ps aux`: Display detailed information about all running processes.
    - `ps -ef`: Display a full listing of processes with their command line arguments.

37. **kill**: Terminate processes.
    - `kill PID`: Send a termination signal to the process with the specified process ID (PID).
    - `killall process_name`: Send a termination signal to all processes with the specified name.

38. **ssh-keygen**: Generate SSH key pairs for secure authentication.
    - `ssh-keygen`: Generate a new SSH key pair.
    - `ssh-copy-id username@hostname`: Copy the public key to the remote host for passwordless SSH authentication.

39. **crontab**: Schedule recurring tasks.
    - `crontab -e`: Edit the user's crontab file to schedule tasks.
    - `crontab -l`: Display the user's crontab entries.
    - `crontab -r`: Remove the user's crontab entries.

40. **man**: Access the manual pages for commands.
    - `manCertainly! Here are a few more commonly used Linux commands with examples:

41. **du**: Estimate file and directory disk usage.
    - `du file`: Display the disk usage of the file.
    - `du -h directory`: Display the disk usage of the directory in human-readable format.
    - `du -sh directory`: Display the total disk usage of the directory in human-readable format.

42. **find**: Search for files and directories based on various criteria.
    - `find directory -name filename`: Search for files or directories with the specified name inside the given directory.
    - `find directory -type f`: Search for files only within the given directory.
    - `find directory -type d`: Search for directories only within the given directory.
    - `find / -size +1G`: Search for files larger than 1GB starting from the root directory ("/").

43. **grep**: Search for text patterns in files.
    - `grep pattern file`: Search for the specified pattern in the file.
    - `grep -r pattern directory`: Search for the pattern recursively in files within the specified directory.
    - `grep -i pattern file`: Search for the pattern in a case-insensitive manner.
    - `grep -v pattern file`: Display lines that do not match the pattern.

44. **sed**: Stream editor for text manipulation.
    - `sed 's/old/new/' file`: Replace the first occurrence of "old" with "new" in each line of the file.
    - `sed 's/old/new/g' file`: Replace all occurrences of "old" with "new" in each line of the file.
    - `sed '/pattern/d' file`: Delete lines that match the pattern in the file.

45. **awk**: Text processing and manipulation tool.
    - `awk '{ print $1 }' file`: Print the first field of each line in the file.
    - `awk '/pattern/ { print $2 }' file`: Print the second field of lines that match the pattern in the file.

46. **ps**: Display information about active processes.
    - `ps`: Display information about processes owned by the current user.
    - `ps aux`: Display detailed information about all running processes.
    - `ps -ef`: Display a full listing of processes with their command line arguments.

47. **kill**: Terminate processes.
    - `kill PID`: Send a termination signal to the process with the specified process ID (PID).
    - `killall process_name`: Send a termination signal to all processes with the specified name.

48. **ssh-keygen**: Generate SSH key pairs for secure authentication.
    - `ssh-keygen`: Generate a new SSH key pair.
    - `ssh-copy-id username@hostname`: Copy the public key to the remote host for passwordless SSH authentication.

49. **crontab**: Schedule recurring tasks.
    - `crontab -e`: Edit the user's crontab file to schedule tasks.
    - `crontab -l`: Display the user's crontab entries.
    - `crontab -r`: Remove the user's crontab entries.

50. **man**: Access the manual pages for commands.
    - `man command`: Display the manual page for the specified command, providing detailed information and usage instructions.
