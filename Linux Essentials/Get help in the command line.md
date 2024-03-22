# Get help in the command line

## Objective

To use the man and whatis commands to get information on other commands and how they work. To also use the apropos command to search the manual page for a command with a specified string.

### Skills Learned

- get manuals of commands
- get one line descriptions of commands
- use apropos to search manual pages

### Tools Used

- BASH shell

## Steps

**1)** **<ins>Learn more about help commands</ins>**  

whatis command is usful when you can’t quite remember what a command does and want a quick reminder

*Fig 1: whatis cat - show a one line direcription of cat*  
![image](https://github.com/RyenHY/Linux/assets/161639514/ee5d76a2-3624-4539-8f87-df4dd1307bb9)
<br/><br/>
*Fig 2: man cat - show more details about cat*
![image](https://github.com/RyenHY/Linux/assets/161639514/c5f24772-a35a-4431-adbc-d603e4866cd7)
etc...
<br/><br/>
**Note:** You can output more information one line at a time by pressing the ENTER key or output the next page of the manual by pressing the space bar. Press Q to exit this manual page
<br/><br/>
*Fig 3: apropos -a first part file - to find a command that returns the first part of a file*
![image](https://github.com/RyenHY/Linux/assets/161639514/52568b08-e25f-47f2-b1e2-e2aee1e963e7)
<br/><br/>
**Note:** There is no right and wrong when using apropos in terms of keywords. Think of it as a very focused search. It will only return commands that correspond to keywords you supply. The -a option will limit results to only those commands that match all keywords supplied.
<br/><br/>

**2)** **<ins>Explore the useradd command</ins>**  
<br/>
Use man command to explore commands
<br/><br/>
*Fig 4: man useradd - show details about useradd* 
![image](https://github.com/RyenHY/Linux/assets/161639514/4f2daf8c-d0b0-4809-a6cc-203036dec607)
<br/><br/>

**3)** **<ins>Compare the rm and rmdir commands</ins>**  
<br/>
Use whatis command to compare commands
<br/><br/>
*Fig 5: use whatis to quickly compare commands* 
![image](https://github.com/RyenHY/Linux/assets/161639514/77976bbf-1cde-49b4-a558-d67c0df24d5d)
<br/><br/>
**Note:** This will require entering two commands
<br/><br/>

**4)** **<ins>Determine which command to use</ins>**  
<br/>
Use apropos command to find commands
<br/><br/>
*Fig 6: apropos -a create new group - find Linux command to create new groups* 
![image](https://github.com/RyenHY/Linux/assets/161639514/0f19ef52-994a-4a5a-b7fb-5ff18bd60b69)
<br/><br/>
