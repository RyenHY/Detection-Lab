# Add and manage users with Linux commands

## Objective

To use the useradd, usermod, userdel, and chown commands to manage user access in the Linux Bash shell

### Skills Learned

- add users to the system with useradd
- modify existing users with usermod
- delete users from the system with userdel and groupdel
- change the ownership of a file or directory with chown
- use sudo command for temporary root (super user) privileges

### Tools Used

- BASH shell

## Steps

**1)** **<ins>Add a new employee to the system and then to their primary group</ins>**  

*Fig 1: useradd - Add a new user*  
![image](https://github.com/RyenHY/Linux/assets/161639514/b92ed34a-d208-4043-92c6-f23741142187)
<br/><br/>
*Fig 2: usermod - Add the new user to the research_team group*
![image](https://github.com/RyenHY/Linux/assets/161639514/11e17e3d-2072-45eb-9882-f2fbc6b6f2b7)
<br/>
**NOTE:** Must user sudo before all of these admin commands
<br/><br/>

**2)** **<ins>Make this employee the owner of a file related to a particular project</ins>**  
<br/>
*Fig 3: chown - Assign file ownership* 
![image](https://github.com/RyenHY/Linux/assets/161639514/0f93c64f-38d7-45b5-bdb1-adaf3969b945)
<br/><br/>
**NOTE:** Must user full filepath or cd into directory
<br/><br/>

**3)** **<ins>Add the new employee to a supplementary group</ins>**  
<br/>
*Fig 4: usermod -a -g - Add the user to a secondary group* 
![image](https://github.com/RyenHY/Linux/assets/161639514/c64253a4-1d52-4a5e-a2db-67666c66e598)
![image](https://github.com/RyenHY/Linux/assets/161639514/934b8f5b-be65-433b-bcb3-3eb0a89f80e9)
<br/><br/>
**NOTE:** Must add a space between the command options 
<br/><br/>

**4)** **<ins>Delete the employee from the system</ins>**  
<br/>
*Fig 5: userdel - Delete a user* 
![image](https://github.com/RyenHY/Linux/assets/161639514/9f1449db-b16a-4f3a-9050-d4f45991c956)
<br/><br/>

**NOTE:** When a new user is created in Linux, a group with the same name as the user is automatically created and the user is the only member of that group. After removing users, it is good practice to clean up any such empty groups that may remain behind with groupdel.
