# Manage authorization

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
![image](https://github.com/RyenHY/Linux/assets/161639514/8776f0ea-f835-4f45-b1e3-18b66c1d73bb)
<br/><br/>
**NOTE:** Files that start with "." are hidden.
<br/><br/>

**2)** **<ins>Check whether any files have incorrect permissions and change the permissions</ins>**  
<br/>
*Fig 2: Changing file permissions for project_k.txt and project_m.txt* 
![image](https://github.com/RyenHY/Linux/assets/161639514/88469e3b-7012-41d7-8fc0-abfbefb328e4)
<br/><br/>
**NOTE:** The file project_k.txt shouldn't be writable by others and project_m.txt is a restricted file and should not be readable or writable by the group or other.
<br/><br/>

**3)** **<ins>Check and modify the permissions to remove any unauthorized access</ins>**  
<br/>
*Fig 3: Change multiple permissions on a hidden file* 
![image](https://github.com/RyenHY/Linux/assets/161639514/c49bed71-c4ce-48f5-a937-44f79ed97a24)

*Fig 4: Change directory permissions* 
![image](https://github.com/RyenHY/Linux/assets/161639514/429c14ac-87df-4dee-a28a-695d050dfef2)
<br/><br/>
**NOTE:** You should be in the projects directory while managing the permissions of its subdirectory drafts.
