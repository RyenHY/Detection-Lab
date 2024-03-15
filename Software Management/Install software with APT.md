# Install Software with APT

## Objective

To install and uninstall applications in Linux. Use Linux commands in the Bash shell and Advanced Package Tool (APT) package manager to install and uninstall the Suricata and tcpdump applications.  

### Skills Learned

- Confirm APT is installed in Bash
- Install Suricata with APT
- Uninstall Suricata with APT
- Install tcpdump with APT
- List installed applications
- Reinstall Suricata with APT

### Tools Used

- BASH shell
- Advanced Package Tool (APT)

## Steps

**1)** **<ins>Confirm that APT is installed on the Linux Bash shell:</ins>**  

When installed, apt displays basic usage information when you run it. This includes the version information and a description of the tool.
<br/>   
*Fig 1: APT* 
![image](https://github.com/RyenHY/Linux-Lab/assets/161639514/e6c54d27-8160-46b4-b502-5239cb61da43)
<br/><br/>

**2)** **<ins>Use APT to install the Suricata application and confirm that it is installed</ins>**  

When you install an application with APT, the output displays details of all the software to be installed. This may include additional applications that depend on the new software. These additional applications are called the dependencies of the software to be installed
<br/><br/>
*Fig 2: Suricata Install Packages* 
![image](https://github.com/RyenHY/Linux/assets/161639514/fd193ac5-2e35-45da-a5d4-2cb1e5399e2f)
<br/><br/>
*Fig 3: Suricata Install* 
![image](https://github.com/RyenHY/Linux/assets/161639514/dd2d9813-c1aa-4995-a242-6884a16e2216)
<br/><br/>
*Fig 4: Suricata Install Complete* 
![image](https://github.com/RyenHY/Linux/assets/161639514/d7297274-ca0e-4cb7-8005-7538353ec556)
<br/><br/>
*Fig 5: Verify Suricata Install* 
![image](https://github.com/RyenHY/Linux/assets/161639514/cc605d02-8f53-4a57-87b0-c25347b71325)
<br/><br/>

**3)** **<ins>Uninstall the Suricata application</ins>**  
<br/>
*Fig 6: Suricata Uninstall* 
![image](https://github.com/RyenHY/Linux/assets/161639514/bfb3235f-5b4e-4d9e-b7d8-368896f91f3c)
<br/><br/>
*Fig 7: Suricata Uninstall Complete* 
![image](https://github.com/RyenHY/Linux/assets/161639514/606d83e2-7781-4863-8cc4-0415d03530a7)
<br/><br/>
*Fig 8: Verify Suricata Uninstall* 
![image](https://github.com/RyenHY/Linux/assets/161639514/f597cc8f-c2ac-4d89-bfbe-9fa1463cd1e4)
<br/><br/>

**4)** **<ins>Install tcpdump</ins>**  
<br/>
*Fig 9: tcpdump Install* 
![image](https://github.com/RyenHY/Linux/assets/161639514/54d61df7-f893-4b44-8dad-b33e533d14a9)
<br/><br/>

**5)** **<ins>List the installed applications</ins>**  

It's important to be able to validate that the correct applications are installed. Often you may want to check that the correct versions are installed as well. This produces a long list of applications in alphabetical order because Linux has a lot of software installed by default.
<br/><br/>
*Fig 10: Use APT to list installed applications* 
![image](https://github.com/RyenHY/Linux/assets/161639514/85ebc19d-245a-4d1d-af99-c5f923ef1e10)
![image](https://github.com/RyenHY/Linux/assets/161639514/0c9e4424-2657-4799-bc37-45dfd8fd923a)
<br/><br/>

**6)** **<ins>Reinstall the Suricata application and confirm that both applications are installed</ins>**  

When reinstalling, not all dependancies need to be redownloaded.
<br/><br/>
*Fig 11: Suricata Reinstall* 
![image](https://github.com/RyenHY/Linux/assets/161639514/7dc9eb4a-2cd4-48d1-8fef-141d01005ad1)
<br/><br/> 
*Fig 12: Suricata Reinstall Complete* 
![image](https://github.com/RyenHY/Linux/assets/161639514/b3ee03d5-6545-49fa-879b-024f38383a25)
<br/><br/>
*Fig 13: Suricata now listed as an installed application* 
![image](https://github.com/RyenHY/Linux/assets/161639514/614b8565-9caf-46d8-8948-f24cd71e9f69)
<br/><br/> 



