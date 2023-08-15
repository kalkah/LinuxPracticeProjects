# DOCUMENTATION FOR LINUX PRACTICE PROJECT

## This Project focus on Linux skill enhanacement

### FILE MANIPULATION

After launching the ubuntu virtual machine the following command was run:

**`sudo apt upgrade`**

Below is the output of the command above

<img width="476" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/1162f87c-811b-4454-b361-d6b32af9d0d3">

#### pwd Command is used to show the path of the current working directory

**`pwd`**

The output of the command above is shown below:

<img width="273" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/3756f46b-7e83-41e6-a9a8-9daa8836c89b">

#### cd command is used to navigate through files and directory.

The command below is used to compltely switch to a new directory 

**`cd DevOps_Folder`**

<img width="459" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/727958e8-ac7b-4c58-9286-2280aeac069e">

The command below is used to move one directory up from the current directory

**`cd ..`**

<img width="320" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/be709402-1b77-4b56-9779-a598238ad790">

#### ls command is used to list files and directories within a system. An output of ls command is shown below

**`ls`**

<img width="443" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/4f8fa017-4432-4526-a3a3-5f604c416bb9">

The command below shows other directories content

**`ls DevOps_Folder`**

<img width="307" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/ebbdaf7e-ace2-4cd9-8d1c-53f881a348ef">

Different flags can be added to the ls command, some examples are shown below

**`ls -R`**  list all the files in the subdirectories

**`ls -a`**  show all the files in the subdirectories including both hidden and visible files

**`ls -1h`**  show the files sizes

<img width="916" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/7d75268c-1e46-4f85-acc3-cdfb708b941b">

#### cat command is used to combines and write file content to standard output

The output of **`cat DevOps`** is hown below

<img width="395" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/9961c091-4503-4d50-a2ac-3821202a0ccd">

**`cp`** command was used to copy files and their content. A sample output is shown below

<img width="564" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/45b3d040-61d0-4846-a8c9-7a0b2de73f59">

The command **`cp file1.txt file2.txt file 3.txt /home/vboxuser/Documents`** was used to copy several files from a direcotry to another directory. The output is shown below

<img width="756" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/50d821f7-1d7a-4085-a2d2-76581114969d">

The command **`cp file1.txt file2.txt`** was used to copy the content of file1 to file3. The output is shown below

<img width="458" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/bb530657-db39-443f-810a-aec0f7f0167c">


The command **`cp -R /home/vboxuser/DevOps  /home/vboxuser/Documents`** was used to copy the entire content of DevOps directory to the Documents directory. The output is shown below

<img width="683" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/74f68238-8306-4971-a834-3d50e49cad7b">

#### mv command is used to move file and directories. it does not produce output on the terminal.

The command below is used to move inside_Folder from Documents directory to DevOps_Folder directory.

**`mv inside_folder /home/vboxuser/DevOps_Folder`**

<img width="760" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/e79181b2-0943-41e7-b28d-3b65374f4175">

The commad **`mv file1.txt file10.txt`** is used to rename file1.txt. The output is shown below.

<img width="524" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/242ea888-c89b-4e51-8716-5b23a34aac17">

**`mkdir Music`** command was used to create a new directory named Music. The output is shown below

<img width="409" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/3158f213-1840-46f1-92b7-150a85a77369">

**`mkdir Music/Song`** command was used to create a new directory named Song inside Music direcotry. The output is shown below

<img width="439" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/fa592c0f-336c-48f1-85c4-4f0500d279fd">

**`rmdir -p Music/Song`** command was used to delete the Music/Song directory. rmdir is used to permanentlt delete empty directory. The output is shown below

<img width="694" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/07a1832f-7079-42a6-8644-069eb5a4ab23">

**`rm file1.txt`** and **`rm file2.txt file3.txt file4.txt`** commands are used to remove a single file and multiple files. The ouput is shown below

<img width="536" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/f6bb8a05-9584-43a0-ab3d-f2b6f8221932">

**`touch file6.txt`** command wa used to create an empty file named file6. The output is shown below.

<img width="448" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/bd361fc2-356b-4ec0-9050-4b266e600790">

**`locate -i school*note`** command is used to seacrh the database for any file that contain the school or note, the flag -i is used so that the search will not be case sensitive. The output is hown below



**`find /home -name DevOps`** command was used to find a file named DevOps in the home directory. The output is shown below

<img width="376" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/7eeb00ba-87ec-4f40-a1a4-183906dc2394">

**`grep note Documents/file6.txt`** command was used to find a word by searching through all the text in a specific file. grep is global regular expression. The output is shown below.

<img width="474" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/534bf19a-cb08-4236-9fde-7da34eceefc1">


**`df -h`** command was used to report system disk sapce usage. The output is shown below.

<img width="542" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/6e87fa91-dce3-4bc1-8544-229b6dce9916">


**`du /home/vboxuser/Documents`** command was used to check how nuch space Documents directory takes up.

<img width="399" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/6acadaef-b643-4e40-8cb0-adf3fa44f8a3">

**`head DevOps`** command shows the first 10 lines of DevOps file.

<img width="496" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/15653081-01ae-4421-863a-35e95c9dbeb9">

**`tail -n DevOps`** shows the last ten lines of DevOps file. It allows user to check whether the file has new data or error message

<img width="676" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/d86f9163-0551-4a47-8750-474667d4134f">

**`diff DevOps DevOps2`** command was used to compare content of 2 files line by line and display the part that do not match. It can be used to alter a command instead of rewriting the entire source code.

<img width="734" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/cc5f1a3b-e62a-4a92-9d66-aa6618e003ea">

**`tar -cvf DevOps2 /home/vboxuser`** was used to archive /home/vboxuser directory into tar file named DevOps2. the cvf flag stand for c - create a new archive, v - verbose, show the update on the screen f - file name. The output is long, part of the output is shown below.

<img width="500" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/82d6d7dc-6126-4a92-b37f-89af2bca38cb">


### FILE PERMISSION AND OWNERSHIP

**`chmod 777 DevOps2`** command was used to allow the users to have read, write and execute permission on the file. There are three user in Linux - Owner, group members and others.rwxrwxrwx numeric value is 777 

<img width="498" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/c78ac380-c9d0-4720-a97d-7d0f6e7dd305">

**`chown linuxuser2 file10.txt`** command was used to make linuxuser2 the owner of file10.txt.  

<img width="354" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/3b8068d6-51b2-4aeb-9c18-889472c69bff">

Jobs command is used to list the jobs that you are running in the background and in the foreground. The prompt returned with no information because no jobs are present

<img width="275" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/a2fde27e-d50d-4f8f-845d-0ddd6469c2b2">

**`kill [signal_option] PID`** command is usually used to terminate an unresponsive program manually. The process identification (PID) must be known To kill a program. 

There are 64 signal options, SIGTERM and SIGKIll are the two most commonly used. SIGTERM is the default if signal option was not specified when entering the **kill** command. SIGTERM request a program to stop running and gives it sometime to save all its progress.
SIGKILL forces the program to stop and all unsaved progress will be lost.

**`ps ux`** command shows the process identification number.

**ping** command is used to check whether a network or a server is reachable.

**`ping google.com`** 

<img width="649" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/d576f7f3-44ea-4b07-a3b2-943e819abfaa">

**`wget`** command let you download files from the internet.

**`wget https://wordpress.org/latest.zip`**

<img width="779" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/acfe4c95-7f9b-4c6e-b8f5-6983b325d2a4">

**`umame`** command provide detailed information about the linux system and hardware. flag -a print all the system information. Flag -s prints the kernel name. Flag -n print the system's node hostname

**`umame -a`**

**`umame -s`**

**`umame -n`**

<img width="794" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/760813ea-a246-4f0a-b7bf-a69fb8a9a5f4">

**`top`** command display all the running processes and dynamic real-time view of the current system. It provide resource utilisation from CPU to memory usage.

<img width="611" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/2b62d1a3-6fc9-4dcd-a245-698023a0fe86">
<img width="874" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/0c2e0efa-1646-4e16-bdce-5fd57f65e276">

**`history`** command list up to 500 previously executed command, it allow us to use the commands without re-entering. sudo priviledge is require to to execute this command. The output is long, a snippet of the output is shown below.

<img width="509" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/58dd7ef9-4157-46df-8e5d-ac17fc7e45a8">


























