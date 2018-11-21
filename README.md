# Honeypot
During the experiment, I deployed three honeypots. They are Cowrie, Dionaea with HTTP, and Snort. Among the three, Dionaea has the highest number of attacks and Cowrie has the least. While doing the emperiment, I also encountered several issues. One of them happened when the mhn server is not showing any attacks after I deployed honeypot. I figured out that for unknown reason, my mhn admin has its memory overutilized. After I upgraded it to 1.7 GB of memory, the IP address of the mhn admin changed. So I deleted all honeypots that related to the old mhn admin and re-deployed the honeypots with the new IP address. And finally, the attacks showed up in the mhn server after my correction. 

Cowrie:
  - Number of Attacks:
  
Dionaea:
  - Number of Attacks:
  
Snort:
  - Number of Attacks:
  
