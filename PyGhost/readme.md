`Pwn`, `Misc`, `demo`, `difficulty: Schrödinger`

This is an LPE(Local Privilege Escalation) challenge. Your task is to pop a highly-privileged(`nt authority\\system`) cmd.exe as a low-privileged user. Follow these steps to deploy the challenge locally:  

1. download and install the virtual machine from: [https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/](https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/)  
2. execute the installer (installer.exe in the attachment) as Administrator  
3. the installer will set up the vulnerable component. You can then attempt to find the vulnerability and exploit it  

Notes about the demo:  
1. Send your `exploit archive file` to demo@realworldctf.com and DM @M4x on Discord when you're ready. Meanwhile, the email should also contains your team name and team token  
2. You can choose to demo your exploit publicly or privately, according to your preference. If you choose to demo publicly, the entire process will be visible to everyone, so remember to remove sensitive information. If you choose to demo privately, we will set up a private discord channel that only includes the admin and your team members  
3. Our demo VM is slightly configured, including:  
   a. Windows Defender is disabled. You don't have to contend with it.  
   b. A standard user(not in the Administrator group, with the username being `ctf`) is created for demo purposes. We will run your exploit in the context of the standard user.  
4. If your exploit needs multiple steps, please batch them in a single file. We will only execute one of your files and then wait for the result without more user interaction  

I will not accept more than 3 emails per team. If you really need more, you will need to explain to me in detail why you messed up your first 3 tries and convince me that you deserve a 4th chance.   
The running time for each try cannot exceed 3 minutes.  

I will reward you with the flag if the highly-privileged cmd.exe pops up.  


[attachment](https://rwctf.oss-accelerate.aliyuncs.com/PyGhost_5878b9faae5d9992014e5a7da12c9317.zip)
