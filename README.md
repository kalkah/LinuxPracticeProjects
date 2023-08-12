# DOCUMENTATION FOR LINUX PRACTICE PROJECT

## This Project focus on Linux skill enhanacement

### FILE MANIPULATION

After launching the ubuntu virtual machine the following command is run:

**`sudo apt upgrade`**

Below is the output of the command above

!<img width="476" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/1162f87c-811b-4454-b361-d6b32af9d0d3">

#### pwd Command is used to show the path of the current working directory

**`pwd`**

The output of the command above is shown below:

![image](https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/304f471a-65a2-49e7-bd84-2ce79482c0b7)

#### cd command is used to navigate through files and directory.

The command below is used to compltely switch to a new directory 

**`cd DevOps_Folder`**

!<img width="459" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/727958e8-ac7b-4c58-9286-2280aeac069e">

The command below is used to move one directory up from the current directory

**`cd ..`**

!<img width="320" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/be709402-1b77-4b56-9779-a598238ad790">

#### ls command is used to list files and directories within a system. An output of ls command is shown below

**`ls`**

!<img width="443" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/4f8fa017-4432-4526-a3a3-5f604c416bb9">

The command below shows other directories content

**`ls DevOps_Folder`**

!<img width="307" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/ebbdaf7e-ace2-4cd9-8d1c-53f881a348ef">

Different flags can be added to the ls command, some examples are shown below

**`ls -R`**  list all the files in the subdirectories

**`ls -a`**  show all the files in the subdirectories including both hidden and visible files

**`ls -1h`**  show the files sizes

!<img width="916" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/7d75268c-1e46-4f85-acc3-cdfb708b941b">

#### cat command is used to combines and write file content to standard output

The output of **`cat DevOps`** is hown below

!<img width="395" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/9961c091-4503-4d50-a2ac-3821202a0ccd">

**`cp`** command was used to copy files and their content. A sample output is shown below

!<img width="564" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/45b3d040-61d0-4846-a8c9-7a0b2de73f59">

The command **`cp file1.txt file2.txt file 3.txt /home/vboxuser/Documents`** was used to copy several files from a direcotry to another directory. The output is shown below

!<img width="756" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/50d821f7-1d7a-4085-a2d2-76581114969d">

The command **`cp file1.txt file2.txt`** was used to copy the content of file1 to file3. The output is shown below

!<img width="458" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/bb530657-db39-443f-810a-aec0f7f0167c">


The command **`cp -R /home/vboxuser/DevOps  /home/vboxuser/Documents`** was used to copy the entire content of DevOps directory to the Documents directory. The output is shown below

!<img width="683" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/74f68238-8306-4971-a834-3d50e49cad7b">

#### mv command is used to move file and directories. it does not produce output on the terminal.

The command below is used to move inside_Folder from Documents directory to DevOps_Folder directory.

**`mv inside_folder /home/vboxuser/DevOps_Folder`**

!<img width="760" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/e79181b2-0943-41e7-b28d-3b65374f4175">

The commad **`mv file1.txt file10.txt`** is used to rename file1.txt. The output is shown below.

!<img width="524" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/242ea888-c89b-4e51-8716-5b23a34aac17">

**`mkdir Music`** command was used to create a new directory named Music. The output is shown below

!<img width="409" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/3158f213-1840-46f1-92b7-150a85a77369">

**`mkdir Music/Song`** command was used to create a new directory named Song inside Music direcotry. The output is shown below

!<img width="439" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/fa592c0f-336c-48f1-85c4-4f0500d279fd">

**`rmdir -p Music/Song`** command was used to delete the Music/Song directory. rmdir is used to permanentlt delete empty directory. The output is shown below

!<img width="694" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/07a1832f-7079-42a6-8644-069eb5a4ab23">

**`rm file1.txt`** and **`rm file2.txt file3.txt file4.txt`** commands are used to remove a single file and multiple files. The ouput is shown below

!<img width="536" alt="image" src="https://github.com/kalkah/LinuxPracticeProjects/assets/95209274/f6bb8a05-9584-43a0-ab3d-f2b6f8221932">



