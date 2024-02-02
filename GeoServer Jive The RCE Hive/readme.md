`score:500` `solve_count:0`

`Web`, `Clone-and-Pwn`, `difficulty:Schr\u00f6dinger`  

Welcome, seekers of cyber lore,  
To a challenge like none before.  
In a world where maps are key,  
GeoServer's the tool, you see.  

It's set on Windows, standing tall,  
With Tomcat running, serving all.  
But lurking deep, a bug does hide,  
An RCE gap, wide and wide.  

Your mission, should you choose to play,  
Is to exploit in a clever way.  
Use your skills, be sharp and keen,  
In the code, where not easily seen.  

Find the flaw, make your move,  
Let your savvy cyber groove  
Turn the tide, and gain control,  
In this digital escapade role.  

So embark on this virtual quest,  
Put your hacking skills to the test.  
In this GeoServer jive,  
Find the hive where RCEs thrive.  

Can you dive into the code,  
On this cyber treasure road,  
And emerge, with flags in hand,  
As the finest hacker in the land?  

`nc 47.89.213.235 1337`  

[attachment](https://github.com/chaitin/Real-World-CTF-6th-Challenges/releases/download/x/GeoServer-Jive_d252d8eb13661a56ac7d0185bd7ddf40.zip)

Hints 1:
 - First of ALL: for the expected solution, you MUST following the README.txt file to deploy the geoserver.
 - The expected solution is a combined Pre-auth RCE vulnerability of stable version of geoserver at 2.24.1 (just found that geoserver lastest released version 2.24.2, don't worry, it's is also vulnerable to expected solution), in more detail, it's an pre-auth vulnerability combined with post-auth RCE vulnerability.
 - For the pre-auth vulnerability, your mission is to find an 'abitrary file read' vuln (not a really 'abitrary', but is sufficient for you to obtain admin's privilege), after then, you can seek for post-auth RCE on geoserver 2.24.1 or geoserver 2.24.2 if you want ;)
 - The deployed machine is in an isolated network therefore it is not vulnerable to any oob attacks.
