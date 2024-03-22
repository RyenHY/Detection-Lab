Manage authorization

## Objective

To use Linux commands to configure authorization of files and directories.

### Skills Learned

- use ls options to display authorization
- use chmod to change file and directory permissions

### Tools Used

- BASH shell

## Steps

**1)** **<ins>Check the user and group permissions for all files in the projects directory</ins>**  

*Fig 1: Check file and directory details*  

<br/><br/>

**2)** **<ins>Check whether any files have incorrect permissions and change the permissions</ins>**  
<br/>
*Fig 2: Using pipe character (|) with grep to list files with Q1 in name* 
![image](https://github.com/RyenHY/Linux/assets/161639514/4cd8ff2d-b531-40aa-a621-7a1ce5906016)
*Fig 3: Using pipe character (|) with grep to list files with access in name* 
![image](https://github.com/RyenHY/Linux/assets/161639514/6c7cf617-d255-44fb-81df-5f527e3a7731)
<br/><br/>
**NOTE:** Piping sends the standard output of one command to the standard input of another command for further processing. In the example, the output of the grep command is piped to the ls command and the output displayed in the shell.
<br/>

**3)** **<ins>Check and modify the permissions to remove any unauthorized access</ins>**  
<br/>
*Fig 4: Search the Q2_deleted_users.txt file for the username jhill* 
![image](https://github.com/RyenHY/Linux/assets/161639514/accf4bd0-ce54-4bf4-9c88-3c28471317c2)
*Fig 5: Search the Q4_added_users.txt file for human resources department* 
![image](https://github.com/RyenHY/Linux/assets/161639514/565eff77-30b0-4876-befd-808f8568c602)
<br/><br/>
**NOTE:** In order for grep to interpret a string of two or more words correctly, you must enclose it in quotes ("Human Resources").
