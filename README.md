# SSHRanger
Some months after PassScript, I returned to my college computer room. One of the days, bored, I decided to setup
an SSH server in several computers in order to connect to them and have fun with them during the class (my classmates
 didn't know about SSH until they saw their laptops were getting 'hacked'). 
 
The experiment succeeded, but soon I wanted to go farther: what if I created a script to map all the IPs in a network 
(i.e. my classroom) and try to SSH them so as to know which of them were ready to connect? The computers' IP addresses changed 
everyday as they weren't configured as static, and a USB-to-Ethernet adapter needed to be used due to the bad state of the 
laptops' Ethernet ports, making them to get an IP slighly different to the most common ones: xxx.xxx.2.xxx.

...and the idea came to my mind. Spent some days thinking about the script layout, and wrote a very basic version (which I 
couldn't try the last day of computer room session due to a network failure), and then I left the project. Some days ago I 
finished polishing some details and debugging some loop related errors, and now I can say the first version of SSHRanger is 
complete. However, some updates could be added at any moment...
