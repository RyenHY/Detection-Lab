# Manage files with Linux commands

## Objective

Use Linux commands to modify a directory structure and the files it contains. Reorganise /home/analyst A to B below:

**A)**  
![image](https://github.com/RyenHY/Linux/assets/161639514/c37be964-f9bf-4c40-8a8d-41840d6079bf)

**B)**  
![image](https://github.com/RyenHY/Linux/assets/161639514/c3e4479d-a8c2-421d-a366-ba6118224dce)

### Skills Learned

- creating, removing, and editing directories and files
- nano text editor to add text to a file

### Tools Used

- BASH shell
- nano CLI text editor

## Steps

**1)** **<ins>Create a new subdirectory called logs in the /home/analyst directory</ins>**  

*Fig 1: Create a directory and verify*  
![image](https://github.com/RyenHY/Linux/assets/161639514/5f9d4a76-f8bc-451e-820f-a049374de663)
<br/><br/>

**2)** **<ins>Remove the temp subdirectory</ins>**  
<br/>
*Fig 2: Remove a directory and verify* 
![image](https://github.com/RyenHY/Linux/assets/161639514/727a839c-b575-4aa7-8a36-6c94e9ddabd3)
<br/><br/>

**3)** **<ins>Move the Q3patches.txt file to the reports subdirectory and delete the tempnotes.txt file</ins>**  
<br/>
*Fig 3: Move Q3patches.txt to reports and verify* 
![image](https://github.com/RyenHY/Linux/assets/161639514/9ef4e6d9-e8ac-4380-bba1-6483266d28e3)
<br/>

*Fig 4: Remove the tempnotes.txt file and verify* 
![image](https://github.com/RyenHY/Linux/assets/161639514/8e351d86-9b52-4d7a-8772-4be827a9c6bb)
<br/><br/>

**4)** **<ins>Create a new tasks.txt file in the notes subdirectory, describing the tasks performed</ins>**  
<br/>
*Fig 5: Create texts.txt and verify* 
![image](https://github.com/RyenHY/Linux/assets/161639514/55a67ced-dcb0-458f-aae3-1dd08324316a)
<br/>

*Fig 6: Edit texts.txt file* 
![image](https://github.com/RyenHY/Linux/assets/161639514/01cdc0c8-2ae9-45df-90ae-2b4e878ab702)
<br/>
**NOTE:** This action changes the shell from the normal Bash interface to the nano text editor interface.

*Fig 7: nano interface* 
![image](https://github.com/RyenHY/Linux/assets/161639514/59b0ffd3-5f80-4437-98ac-df791d589dce)
<br/>

*Fig 8: Verify file contents with cat* 
![image](https://github.com/RyenHY/Linux/assets/161639514/4093923c-8377-47a4-bbc0-985711c7575b)
<br/><br/>
