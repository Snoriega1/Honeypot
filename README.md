# Honeypot
<hr>
<b><h3>Install Instance in GUI</h3></b>
This was fairly easy just following the instructions in the assignment for this step. I noticed that the actions could be performed in the GUI or in the command line. The instructions were for the command line but as you see in the screenshot below I used the GUI. The steps still corelated to items in the GUI and you just need to pay close attention to enter the configurations into the correct fields.
<img src="https://i.ibb.co/JC2pkhN/Install-Instance-in-GUI-or-GCP-Console.png" alt="Install-Instance-in-GUI-or-GCP-Console" border="0"></a>
<b><h3>Installing Ubuntu Pi</h3></b>
Again this step was very easy if the instructions were followed correctly.
<img src="https://i.ibb.co/VvCnbKw/Installing-Ubuntu-Pi.png" alt="Installing-Ubuntu-Pi" border="0"></a>
<b><h3>Firewall Configs</h3></b>
This step was also very simple, just cut and paste from the assignment instructions. It is important to note though what rules are being implemented and why. As we can see we are allowing traffic in from anywhere and everywhere so that the attackers have easy access to the honeypot and away from more important data.
<img src="https://i.ibb.co/kMBCMQX/Firewall-Configs.png" alt="Firewall-Configs" border="0"></a>
<b><h3>Honeypot was not getting attacks but I fixed the Network Tags and it worked</h3></b>
This is where tings got a little tricky. Either the instructions were not very clear or I missed something in the setup but if the Network tags are not correct the traffic will not be let through. At first I only had network tags for http traffic only. This was not allowing any attacks to my honey pot. I then added the mhn-admin tag and attacks began to flow in. I also changed the tags in the honeypots themselves but I didn't notice the attacks until the chabges were made to the mhn-admin Instance.
<img src="https://i.ibb.co/hWPXwdG/Fixed-the-Network-Tags-and-it-worked.png" alt="Fixed-the-Network-Tags-and-it-worked" border="0"></a>
<b><h3>Here come the Attacks</h3></b>
The attacks began imediately for honeypot 1 and 3 but 2 was a bit slower. Eventuall all honeypots were attacked. 
<img src="https://i.ibb.co/0BFTqjT/Here-come-the-attacks.png" alt="Here-come-the-attacks" border="0"></a>
<b><h3>All Honeypots got attacked</h3></b>
Honeypot 1 I used dionaea which produced the most attacks at 2,211,834.
<img src="https://i.ibb.co/Jsj8XH1/Honeypot-1.png" alt="Honeypot-1" border="0"></a>
Honeypot 2 I used cowrie and had the least attacks at 348.
<img src="https://i.ibb.co/BN42xL3/Honeypot-2.png" alt="Honeypot-2" border="0"></a>
Honeypot 3 I used p0f had the second most with 25,278.
<img src="https://i.ibb.co/VtCnLN6/Honeypot-3.png" alt="Honeypot-3" border="0"></a>
<b><h3>Number of attacks in 24 hours</h3></b>
This was the count of attacks on the last day when I stopped the instances.
<img src="https://i.ibb.co/kQgZfyp/Attacks-last-24-hrs.png" alt="Attacks-last-24-hrs" border="0"></a>
<b><h3>Total Attacks during project</h3></b>
I mentioned the number of attacks above but this is a screenshot of the totals. I had the honeypots running for about five days. It is remarkable to me how many attacks camw through in such a short period of time.
<img src="https://i.ibb.co/B6qYzcj/Total-attacks.png" alt="Total-attacks" border="0"></a>
<b><h3>Resources used in the Billing report</h3></b>
Here is a screenshot of the first page of my billing report which shows the top resources used.
<img src="https://i.ibb.co/vZgzRnP/Billing-sheet.png" alt="Billing-sheet" border="0"></a>
<b><h3>Having trouble getting json file onto host machine</h3></b>
This step was by far the hardest and took the longest and unfortunately I was unable to get the sessions.json file exported to my host machine. I did manage to get a screenshot of part of the file but could not get the whole file uploaded. Below is the file being downloaded but I could cot find it in my host machine. 
<img src="https://i.ibb.co/3WdJcKX/Cant-find-json-file-on-host.png" alt="Cant-find-json-file-on-host" border="0"></a>
This is the json file viewed using the nano command in the ssh terminal.
<img src="https://i.ibb.co/dt7Mywr/json-file.png" alt="json-file" border="0"></a>
