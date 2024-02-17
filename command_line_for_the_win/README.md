command_line_for_the_win is a directory with tasks that test my knowledge of using sftp to transfer files from local machine to remote machine. These are the steps I used to transfer the 3 files:

1. I opened terminal on my local machine.
2. I first navigated to where my screenshots were and after confirming I could see them on my local machine, I proceeded.
3. I typed the sftp command together with my username and hostname. (sftp username@hostname)
4. I was prompted for password and there after I was authenticated and I got the sftp prompt.
5. I tried a number of commands like 'pwd, lpwd, ls, lls' just for testing.
6. I used the 'cd' command to navigate to the directory on the remote machine where I wanted to upload the files.
7. I used the 'put' command to upload the files. (put 'filename')
