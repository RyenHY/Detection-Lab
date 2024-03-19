# Filter with grep

## Objective

To use the grep command and piping to search for files and to return specific information from files.

### Skills Learned

- use grep to search for information contained in files
- use pipe and grep to search for file names that contain specific strings

### Tools Used

- BASH shell

## Steps

**1)** **<ins>Search the file and output only the entries that are for errors</ins>**  

*Fig 1: grep - search for error messages in a log file*  
![image](https://github.com/RyenHY/Linux/assets/161639514/9ecc5aad-c2cd-4345-89be-85e78619abb2)
<br/><br/>

**2)** **<ins>Use pipe character (|) with grep to find file names containing specific strings</ins>**  
<br/>
*Fig 2: Using pipe character (|) with grep to list files with Q1 in name* 
![image](https://github.com/RyenHY/Linux/assets/161639514/4cd8ff2d-b531-40aa-a621-7a1ce5906016)
*Fig 3: Using pipe character (|) with grep to list files with access in name* 
![image](https://github.com/RyenHY/Linux/assets/161639514/6c7cf617-d255-44fb-81df-5f527e3a7731)
<br/><br/>
**NOTE:** Piping sends the standard output of one command to the standard input of another command for further processing. In the example, the output of the grep command is piped to the ls command and the output displayed in the shell.
<br/>

**3)** **<ins>Use grep to search for more file contents</ins>**  
<br/>
*Fig 4: Search the Q2_deleted_users.txt file for the username jhill* 
![image](https://github.com/RyenHY/Linux/assets/161639514/accf4bd0-ce54-4bf4-9c88-3c28471317c2)
*Fig 5: Search the Q4_added_users.txt file for human resources department* 
![image](https://github.com/RyenHY/Linux/assets/161639514/565eff77-30b0-4876-befd-808f8568c602)
<br/><br/>
**NOTE:** In order for grep to interpret a string of two or more words correctly, you must enclose it in quotes ("Human Resources").
